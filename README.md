# crow-server-template

Build and run it with:
```bash
cmake -S . -B build
cmake --build build --target crow_api_server -j4
./build/crow_api_server --host 127.0.0.1 --port 8443
```

# API
```bash
curl -ik https://127.0.0.1:8443/api/health
curl -ik "https://127.0.0.1:8443/api/health?mode=error"
curl -ik https://127.0.0.1:8443/api/cid4/conformer/1
curl -ik https://127.0.0.1:8443/api/cid4/compound
```
