---
layout: page
title: Getting Started
---

This guide offers an overview of the structure and main concepts of Workshop Aurora.

## 1. What is Aurora

Workshop Aurora is a web-based generator for **visual novels** (some of them are called GalGames). It's designed to be the easiest way for creators to build games for all platforms with only story scripts and media materials.

## 2. Try it with the demo

### 2.1. Get the demo repo

Checkout the [git repo for the demo app](https://github.com/project-yoru/aurora-demo-app){:target="_blank"}.

Feel free to fork and edit it before build it.

### 2.2. Peep in the repo structure

| File/Folder | Content |
| - | - |
| config/ | config |
| - application.(yaml,json,cson) | |
| story/ | story |
| resources/ | resources |

## 3. Build it!

### 3.1. Via the web interface

[aurora website](http://aurora.project-yoru.com){:target="_blank"} is the web interface for Aurora.

#### 3.1.1 Sign up and sign in

{:.message}
Currently we only support sign up via github account.

#### 3.1.1 Create a project

Create a project, with the `source` being the git address for the demo app (or the one you forked).

#### 3.1.1 Wait a moment

Wait a moment and download the app.

### 3.2. via CLI

{:.message}
CURRENTLY NOT RECOMMENDED.
We're still working on this in preparation to make it public.

Instead of the [aurora website](http://aurora.project-yoru.com){:target="_blank"}, you may also build your app directly via the <code>aurora-builder</code> CLI tool.

## 4. Try it!

### 4.1. Web version

For the web version, you have to host a http server locally.

- For node.js: `npm install -g http-server && http-server`
- For python2: `python -m SimpleHTTPServer`
- For python3: `python3 -m http.server`

And then just access `127.0.0.1:listening_port` in your browser.

{:.message}
Modern browsers supported only, Google Chrome recommended.

### 4.1. Android version

For the android version, just transfer the file to your device, tweak the `unknown sources` related system setting, and install it.
