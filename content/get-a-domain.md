# Get a domain

Using the Twente.me service, you can get a free domain name, email forwarder, and redirects for your project.

## Setup your domain

Before you proceed, you should already have a website up and running. If you don't know how to get started, [GitHub Pages](https://guides.github.com/features/pages/) is a free service to build and host your site.

1. Fork the [TwenteMe/data](https://github.com/TwenteMe/data) repository
2. Edit the [`cname.json`](https://github.com/TwenteMe/data/blob/master/cname.json) file and add your record:

```json
{
  "your-subdomain": "your-cname-record"
}
```

3. Make a pull request after saving the file

Alternately, you can also [edit the file directly](https://github.com/TwenteMe/data/blob/master/cname.json) by clicking on the Edit (pencil) icon on the top right, and then making a pull request.

### Record details

In place of `your-cname-record`, you should enter where your website should point to. If you're using GitHub Pages, this should be `your-github-username.github.io` and if you're using Netlify, this should be `your-site.netlify.app`.

## Setup your email forwarder

Similar to the above, you can setup an email forwarder, for example `your-name@twente.me` can forward all emails to `your-real-email@example.com`.

1. Fork the [TwenteMe/data](https://github.com/TwenteMe/data) repository
2. Edit the [`emails.json`](https://github.com/TwenteMe/data/blob/master/emails.json) file and add your forwarder:

```json
{
  "your-email": "your-real-email@example.com"
}
```

If you want to forward to multiple emails, you can use an array of email addresses:

```json
{
  "your-email": ["email-1@example.com", "email-2@example.com"]
}
```

3. Make a pull request after saving the file

Alternately, you can also [edit the file directly](https://github.com/TwenteMe/data/blob/master/emails.json) by clicking on the Edit (pencil) icon on the top right, and then making a pull request.

## Get a redirect

## Setup your domain

You can also setup redirects that go from `https://twente.me/example` to `https://your-site.com`

1. Fork the [TwenteMe/data](https://github.com/TwenteMe/data) repository
2. Edit the [`redirects.json`](https://github.com/TwenteMe/data/blob/master/redirects.json) file and add your record:

```json
{
  "your-short-url": "https://your-website.com"
}
```

3. Make a pull request after saving the file

Alternately, you can also [edit the file directly](https://github.com/TwenteMe/data/blob/master/redirects.json) by clicking on the Edit (pencil) icon on the top right, and then making a pull request.
