# <img src='Workflow/icon.png' width='45' align='center' alt='icon'> Alias Homebrew Apps Alfred Workflow

Create shortcuts to Homebrew formula app bundles

<a href='https://alfred.app/workflows/alfredapp/alias-homebrew-apps'>⤓ Install on the Alfred Gallery</a>

## Setup

Set the formulae you want linked in the [Workflow’s Configuration](https://www.alfredapp.com/help/workflows/user-configuration/).

## Usage

Run the Alias Keyword (default: `brewalias`). Homebrew Cellar apps will be aliased into your Applications Folder, allowing them to be indexed and found.

![Alfred search for brewalias](Workflow/images/about/brewalias.png)

![Alfred search for macvim](Workflow/images/about/macvim.png)

To trigger the workflow from a terminal, define a `brewalias` command in your shell’s startup files:

```
alias brewalias='/usr/bin/osascript -e "tell application id \"com.runningwithcrayons.Alfred\" to run trigger \"build\" in workflow \"com.alfredapp.vitor.aliashomebrewapps\""'
```
