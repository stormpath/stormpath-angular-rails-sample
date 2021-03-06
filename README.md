#Stormpath is Joining Okta
We are incredibly excited to announce that [Stormpath is joining forces with Okta](https://stormpath.com/blog/stormpaths-new-path?utm_source=github&utm_medium=readme&utm-campaign=okta-announcement). Please visit [the Migration FAQs](https://stormpath.com/oktaplusstormpath?utm_source=github&utm_medium=readme&utm-campaign=okta-announcement) for a detailed look at what this means for Stormpath users.

We're available to answer all questions at [support@stormpath.com](mailto:support@stormpath.com).


# Stormpath Angular + Ruby on Rails Sample Project

This repository is an example fullstack web application, using Angular.js on the
front-end and Ruby on Rails as back-end.  It uses [stormpath-rails][]
and [stormpath-sdk-angularjs][] to authenticate users, protect your server API,
and render default login and registration screens in your Angular application.

[stormpath-rails]: https://github.com/stormpath/stormpath-rails
[stormpath-sdk-angularjs]: https://github.com/stormpath/stormpath-sdk-angularjs

## 1. Getting Started

To run this example project, you will need to create a [Stormpath][] tenant account.
Please sign up for a free account at https://api.stormpath.com/register

## 2. Installation

Clone this repository, then enter the folder with your terminal and run this
command:

```bash
bundle install
```

If everything is installed successfuly, you can continue on to configuration.

## 3. Configuration

Check if your stormpath env variables are set. Those are used in stormpath configuration config/initilizers/stormpath.rb

## 4. Usage

Start the Rails server

```bash
rails server
```

The application should now be running in your borwser at http://localhost:3000

You can get your API Keys and Application HREF from the
[Stormpath Admin Console][].

[Stormpath]: https://stormpath.com
[Stormpath Admin Console]: https://api.stormpath.com
[stormpath-sdk-angularjs]: https://github.com/stormpath/stormpath-sdk-angularjs
[stormpath-rails]: https://github.com/stormpath/stormpath-rails
