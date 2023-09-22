# Leptos Tailwind Template

You will need the nightly toolchain:

```
rustup toolchain install nightly
```

### Run the project

1. Install trunk

```
cargo install trunk
```

2. Install Tailwind

```
npm install -D tailwindcss
```

3. start tailwind watch and keep it running (scans your files for tailwind classes and puts them into output.css)

```
npx tailwindcss -i ./input.css -o ./style/output.css --watch
```

4. build leptos project in a second console

```
trunk serve --open
```

This should open http://127.0.0.1:8080/ in your browser.
If a process is already running on the port you can kill it with `npx kill-port 8080`

You should see a big orange button, that is changing to blue when you hover it. Otherwise something went wrong.
