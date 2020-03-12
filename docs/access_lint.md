# AccessLint

According to their documentation, AccessLint is:

>AccessLint brings automated web accessibility testing into your development workflow. When a pull request is opened, AccessLint reviews the changes and comments with any new accessibility issues, giving you quick, timely, and targeted feedback, before code goes live.

## Demo

## Setup

Let's create a new Rails app and `cd` into it:

```sh
rails new access_lint_demo
cd access_lint_demo
```

Then setup the database:

```sh
bin/rails db:setup
```

And install dependencies

```sh
bundle install
yarn install
```

Now, let's start the Rails server:

```shell
rails s
```

If you want to run the `webpack-dev-server`, run this in another tab:

```shell
bin/webpack-dev-server
```

If you navigate to `localhost:3000` in your browser, you should see the Rails welcome page:

![rails_welcome_page](./images/rails_welcome_page.jpg)

### Create Repository

Open GitHub and create a new repository. I named mine `access_lint_demo`.

Open your command line again and let's upstream our code.

```sh
git add .
git commit -m "first commit"
git remote add origin https://github.com/YOUR_USERNAME/access_lint_demo.git
git push -u origin master
```

Your code should now be online in your repo.

## Configuration
