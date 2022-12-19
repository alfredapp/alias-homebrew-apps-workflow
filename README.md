# <img src='Workflow/icon.png' width='45' align='center' alt='icon'> Alias Homebrew Apps Alfred Workflow

Create shortcuts to Homebrew formula app bundles

<a href='https://alfred.app/workflows/alfredapp/alias-homebrew-apps'>⤓ Install on the Alfred Gallery</a>

## Usage

Set the formulae you want linked in the workflow’s configuration and run the Alias Keyword (default: `brewalias`). App bundles will be aliased into your Applications directory, allowing them to be indexed and invoked like other apps.

![Alfred search for brewalias](Workflow/images/about/brewalias.png)

You can run the workflow from a Terminal via the External Trigger. The simplest way is to define an alias in your shell’s startup files:

```
alias brewalias='/usr/bin/osascript -e "tell application id \"com.runningwithcrayons.Alfred\" to run trigger \"build\" in workflow \"com.alfredapp.vitor.aliashomebrewapps\""'
```

Then executing `brewalias` in a Terminal will run the Workflow.
