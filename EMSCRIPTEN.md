# Emscripten

## Compile

```
emmake make
```

## Link

```
em++ */*.o *.o -o index.html -sUSE_SDL=2 -sUSE_SDL_MIXER=2 -sASYNCIFY --preload-file gnukem_data/
```
