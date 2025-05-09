This is a quick demo/instance of devbox that is capable of running:
- Helix
- Terraform
- uv
- npm
- and more!

# installation

1. [instructions on the devbox website](https://jetify-com.vercel.app/docs/devbox/installing_devbox/?install-method=wsl)

2. Then, install direnv 
```bash
curl -fsSL https://get.jetify.com/devbox | bash
```

3. Finally, clone this repository and cd into it. After that, use the following command:
```bash
direnv allow
```

4. `cd .. `
5. `cd base-box`

Done!

If you use helix in my terminal by using hx, which if you don\'92t use for text editing will only be available on this directory and no others!

If you have issues, please check the `.envrc` file to see if there is a compatibility issue with it.