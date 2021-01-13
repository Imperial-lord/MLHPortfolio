---
title: WebEgde
layout: page
---

<br>
### Bringing Edge to your Web Performance

## 💥 Introduction

Rise of Web  has heralded the increasing ways in which we optimize Digital Performance. With SEO and Web Performance playing an important part, Developers feel lost around Performance needs. <b>WebEdge</b> aims to fix this 🌐

WebEdge have been introduced to suggest Web Optimizations for the App that can speed up operations and boost productivity ⚡

## 💡 Why did we build it?

As Frontend Developers, Performance plays an important part for Ranking and User Experience. The priority is such that it cannot be avoided any longer. WebEdge provides a Python Package for you to scrap you Website and auto-suggest improvements you can make to improve your Optimization Ranking ♾️

With this Package, we aim to have a unified tool to improve your SEO Ranking with real-time optimizations, that you can fix as a Developer. Sounds interesting? Well it is 🔥

## 🛠️ Usage

That's pretty easy. To ensure that you are able to install everything properly, we would recommend you to have <b>Git</b>, <b>Python</b> and <b>pip</b> installed. You should ideally work with a Virtual Environment, such as `venv` or the `virtualenv` module, to get the best out of the package. 

We will first start with setting up the Local Project Environment:
```BASH
$ git clone https://github.com/HarshCasper/WebEdge.git
$ cd WebEdge
$ virtualenv venv
$ source venv/bin/activate
(venv) $ pip3 install -r requirements.txt
(venv) $ python3 setup.py install
```
Once you run the Commands and get everything fine, we are all set to run the tool ✔️

Let's run the tool now: 
```BASH
(venv) $ webedge -d http://[DOMAIN_NAME]/
```

* For example if your domain is ajitesh13.github.io then your command should be (you can use `http` or `https` in the command according to your needs): 

```BASH
(venv) $ webedge -d https://ajitesh13.github.io/
``` 
Pass your Website to the tool and you will get a generated JSON highlighting all the achievements you have made in SEO Optimization or the warnings being displayed by the same 🔑

**Building using docker**
```bash
$ docker build -t 'app:webedge' .
$ docker run app:webedge
```

## 🛑 External Tools

The Python Files have been linted using [flake8](https://flake8.pycqa.org/) which automatically suggests linting errors and issues with formatting and styling. You can run the `flake8` command with the given configuration in the Project 🍀

We are also making use of DeepSource Analysis, which can be viewed [here](http://deepsource.io/gh/HarshCasper/webEdge). This allows us to identify potential bugs and anti-patterns with each push to the repository, and potentially fix it 🐛

For setting up CI/CD, we are making use of [Travis CI](http://travis-ci.org/). With a simple configuration set-up, we were able to test each build for specific issues, which can be viewed [here](https://travis-ci.org/github/HarshCasper/WebEdge) 🌱

## 📜 LICENSE

[MIT License](https://github.com/HarshCasper/WebEdge/blob/main/LICENSE)