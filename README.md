# Build 
          docker build -f Dockerfile.dev .
# run
          docker run -p 3000:3000 IMAGE_ID
# volume
          docker run -p 3000:3000 -v /app/node_modules -v $(pwd):/app image_id
 
<img width="1417" alt="Screen Shot 2023-02-15 at 8 13 48 PM" src="https://user-images.githubusercontent.com/69278312/219129421-ff5a1db4-2098-4fab-9802-30d8dc62de7f.png">

