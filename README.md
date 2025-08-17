README.md file in your repository at https://github.com/Hanshy44/Hanshy_44/blob/main/README.md 
# Generate an image with Pix-Able
curl -X POST http://localhost:5000/api/generate \
  -H 'Content-Type: application/json' \
  -d '{
    "prompt": "A glowing dragon in the clouds, cartoon style",
    "provider": "openai",
    "ratio": "1:1"
  }'
