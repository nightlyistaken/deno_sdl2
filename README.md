### Deno SDL2

Cross platform and stable bindings to [SDL2](https://www.libsdl.org/index.php). Have fun!

<img align="center" src=https://user-images.githubusercontent.com/62501544/128629366-9f5f4f23-5ec8-4246-b3a7-c540b7286a60.png height="400px">
    
#### Features

- Bindings to Video, Graphics, Font and Mixer subsystems.
- API similar to `Rust-sdl2`
- Not `--unstable`. Uses TCP instead of Deno's traditional plugin system.

#### Example

```typescript
const canvas = new Canvas({ title: "Hello, Deno!", width: 800, height: 400 });

canvas.addEventListener("event", (e: WindowEvent) => {
  console.log(e.detail);
});

canvas.setDrawColor(0, 64, 255, 0);
canvas.clear();
canvas.present();

canvas.start();
```

### License

[MIT](https://opensource.org/licenses/MIT)

  
