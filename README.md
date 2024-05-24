ai-web3-workshop

# Create a NFT collection with the students on the spot

rm -rf node_modules
rm package-lock.json
npm install
npm run build
npx vercel --prod
