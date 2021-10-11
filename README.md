# Disk Notifier Confidence
In this repo I totally arbitrarily display how confident I am about aspects of Disk Notifier.

I may or may not update this repo. But when I do you can check how I feel about different aspects of the project in the Git history. Neat.

Check out my project at [https://disknotifier.com](https://disknotifier.com).

## Developement

Build (compile?) the stylesheet:

```shell
npx tailwindcss -i style.css -o tailwind.css
```

Then in the root of the project do:

```shell
caddy file-server --listen :2015
```
