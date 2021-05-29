# OrLike Example

This directory is a brief example of a OrLike app that can be deployed with Vercel and zero configuration.

## Deployment

Deploy your own OrLike app with Vercel.

[![Deploy to Vercel](https://camo.githubusercontent.com/f209ca5cc3af7dd930b6bfc55b3d7b6a5fde1aff/68747470733a2f2f76657263656c2e636f6d2f627574746f6e)](https://vercel.com/import/project?template=https://github.com/caibingcheng/vercel-orlike)


### How to Create This Example

```index.py```:
```Python
from orlike import app_orlike as app

if __name__ == '__main__':
    app.run()
```

### Deploying From Terminal
You can deploy your new OrLike project with a single command from your terminal using Vercel CLI:
```Shell
vercel
```