#documentasi on youtube:
https://youtu.be/vxTW22y8zV8?si=qzu9YrxSFFnXwSLM

#build  docker
docker build -t heysolana .

$run docker
docker run -it --rm -v $(pwd):/solana-token -v $(pwd)/solana-data:/root/.config/solana heysolana

#creating token
1. solana-keygen grind --starts-with dad:1
2. solana config set --keypair dad-your-token-acount.json
3. solana config set --url devnet (mainet)
4. solana config get
5. Run this to find your solana address => solana address
6. Paste your solana address in the field and enter an amount of SOL you want. 2.5 will be MORE than enough
7. cek this full documentation https://blog.networkchuck.com/posts/create-a-solana-token/


