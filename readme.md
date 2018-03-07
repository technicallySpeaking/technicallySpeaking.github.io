# Technically Speaking

Your friendly neighborhood tech team is working to make tech more accessible.
This project serves as a [repository of past presentations](https://ryanparsley.github.io/technicallySpeaking/)

## Installation

```
bundle install
```

## Development

Typically, jekyll sites are worked on with a dev server running like this:

```
jekyll serve
```

Since this is hosted on Github Pages, there is configuration to make links work with a subfolder.
If you'd rather not have a subfolder use the base url like so:

```
jekyll serve --baseurl=''
```

## Deployment

I have github pages watchin the master branch and automatically deploying.
Everytime a commit is pushed to master, the github pages site will be updated.
You can also have cloudcannon sync with this directory to have a more humane GUI.
