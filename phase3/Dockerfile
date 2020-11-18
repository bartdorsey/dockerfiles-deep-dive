# Step 1: Base image for node build - use alpine for node version 12
#         Name it build-stage

# Step 2: Set the working directory to /app

# Step 3: Add package.json and pacagke-lock.json files

# Step 4: Install dependencies using npm
#   To keep the image small, (force) clean the npm cache after
#   Chain the commands to reduce the number of layers in the image
#   Tip: You can use && in a shell commmand to chain commands

# Step 5: Add React application files to the build-stage

# Step 6: Build the React application

# Step 7: Bring in the base image for NGINX (alpine)

# Step 8: Expose the proper nginx port for http

# Step 9: Set working directory to the html folder for nginx

# Step 10: Copy over the build files from build-stage to the working directory

# Step 11: Add our nginx default.conf file to the /etc/nginx.d folder in the image
