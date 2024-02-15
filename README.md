# llama cpp

## Who is the main publisher?
llama cpp github
https://github.com/ggerganov/llama.cpp/tree/master

## How to build your llama model?
```bash
mkdir build && cd build
cmake ..
cmake --build . --config Release
cd bin
./server -m ../../models/persian_llama_7b.Q4_K_M.gguf
```

Now check your borwser on "localhost:8080"
