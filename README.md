# Build 
          docker build -f Dockerfile.dev .
# run
          docker run -p 3000:3000 IMAGE_ID
# volume
          docker run -p 3000:3000 -v /app/node_modules -v $(pwd):/app image_id
 
<img width="1417" alt="Screen Shot 2023-02-15 at 8 13 48 PM" src="https://user-images.githubusercontent.com/69278312/219129421-ff5a1db4-2098-4fab-9802-30d8dc62de7f.png">

<img width="922" alt="Screen Shot 2023-02-16 at 2 12 36 PM" src="https://user-images.githubusercontent.com/69278312/219374692-b2ea0824-2af3-4c4e-952f-9dfd48d421af.png">

# Executing tests

          docker run -it image_id npm run test
<img width="922" alt="Screen Shot 2023-02-16 at 2 12 36 PM" src="https://user-images.githubusercontent.com/69278312/219381381-9f1527c3-acd0-42e6-a93b-b1cb7aacc971.png">
