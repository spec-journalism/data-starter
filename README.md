A scaffold for data projects with Jupyter Notebook.

## Prerequisites

1. Make sure you have completed all the [Spectate prerequisites](https://github.com/graphicsdesk/spectate#prerequisites).

2. Install [degit](https://github.com/Rich-Harris/degit).

## Setup

1. Make a new directory for your project and [`cd`](http://linuxcommand.org/lc3_man_pages/cdh.html) into it.

2. Copy the scaffold into the directory:

```sh
$ degit graphicsdesk/jupyter-starter
$ mv README.story.md README.md
```

3. Initialize the repository and commit the starter code:

```sh
$ git init
$ git add .
$ git commit -m 'notebook starter scaffold'
```

3. Create a new repository in the `graphicsdesk` organization. Add the remote link, and push up your local repository:

<pre>
$ git remote add origin git@github.com:graphicsdesk/<var>REPOSITORY_NAME</var>.git
$ git push
</pre>
