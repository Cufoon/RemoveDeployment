## Introduction

A tool to delete some deployment of Github repo.

## Usage

π First, clone this repo:

```bash
git clone https://github.com/Cufoon/rmDeployment.git
```

π then write your infomation in **index.html**

```javascript
CufoonAPP.deleteDeployment(
  "YourName", // η¨ζ·ε your github username
  "RepoName", // δ»εΊε your repo name
  "Production", // η―ε’ε your envirenment name
  "Github API Token", // github api token
  "keep" // ζ―ε¦δΏηζζ°ηδΈζ¬‘ι¨η½² 'keep'δΏη 'none'δΈδΏη, whether to keep the latest deployment, 'keep' or 'none'
);
```

π then open index.html in your browser, then click "εΌε§ζ§θ‘" button

you can see some information in console(chrome dev tools).

## Learn more

π [Github API](https://docs.github.com/en/rest)
