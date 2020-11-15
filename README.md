# BackendApiUsingNode
Node with Typescript Learning
# Step 1
npm init

# Step 2
# install the typescript package
npm install typescript -s

# Step 3
# Add tsc: inside package.json to allow transpile .ts files to .js scripts

# Step 4
# This command initializes the typescript project by creating the tsconfig.json file
npm run tsc -- --init

# Step 5
# install express
npm install express -s
# Step 6
# Express and Typescript packages are independent and Typescript does not “know” types of Express classes. Install npm package for the Typescript to recognize the Express types
npm install @types/express -s

# Step 7
# Add app folder and app.ts code  and run "npm run tsc"
