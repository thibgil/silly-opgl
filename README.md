# silly-opgl
Learning OpenGL

## Dependencies
```bash
sudo apt install build-essential g++ libgl-dev libglfw3-dev
```

## Compile Manually
```bash
g++ -fdiagnostics-color=always -g <YOUR_PATH>/silly-opgl/*.cpp <YOUR_PATH>/silly-opgl/glad/*.c -o <YOUR_PATH>/silly-opgl/main -lGL -lglfw
```

## Sources
- [Learn OpenGL](https://learnopengl.com/)
- [Glad Generator](https://glad.dav1d.de/)
