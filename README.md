# Shopify Theme Development Setup using shopify.dev/themes website as reference

```
005
```

## Create a store using shopify partner = d

## Install shopify CLI

## Check shopify CLI version

```
shopify version
gem update shopify-cli
```

## Initialize a new theme using Dawn

```
shopify theme init
  005-chopify
cd 005-chopify
```

## Authenticate with Shopify CLI

```
shopify login --store 005-chopify.myshopify.com
```

## If error use this method

```
shopify logout

web browser
  shopify, logout
  https://005-chopify.myshopify.com/admin
    login, username, password
    Don't close the success notification.

shopify login
```

## Preview your theme

```
shopify theme serve

web browser
  http://127.0.0.1:9292                                                     = local
  https://005-chopify.myshopify.com/admin/themes/128972816552/editor        = Online Store Editor
  https://005-chopify.myshopify.com/?preview_theme_id=128972816552          = Share preview link
```

## Create Github repository

```
new repository
  repository name: 005-chopify
  public
  create repository

copy this: git branch -M main
copy this: git remote add origin git@github.com:angelocdz/005-chopify.git
copy this: git push -u origin main
```


## Create Git repository

```
git init
git status
git add .
git commit -m 'Git initialize'
git log --oneline

git branch -M main
git remote add origin git@github.com:angelocdz/005-chopify.git
git push -u origin main

web browser
  refresh repository
  https://github.com/angelocdz/005-chopify
```

## Push your theme to a new GitHub repo


