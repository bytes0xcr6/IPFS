# Infura
![1_7yVCUf1rZTpgT0_-EQTtiw](https://user-images.githubusercontent.com/102038261/201488203-bc46dc8c-a0da-434b-91a8-97bf31fec1fd.jpg)

### Stepts to upload NFTs

1. Get the API-key and API-key-secret from your Infura account.
2. Upload your image file from your terminal with the next command line:

`curl -X POST -F file=@./<file> “https://ipfs.infura.io:5001/api/v0/add” -u “<API-Key>:<API-Key-Secret>”`

3. You will get a Hash / CID and you will be able to visualize your JPG from IPFS. 

`Here an example: 
https://cristianricharte6test.infura-ipfs.io/ipfs/QmSdQigdQunad8F92xekHcxEvKLKRUeAnTM64VT6cHXBzW`

4. Create the JSON metadata file with all the NFT caracteristics and the IPFS URL for the NFT image.
5. Upload your metadata file from your terminal with the next command line:
6. You will get again a Hash / CID to visualize the Metadata upload to IPFS. 

`Here an example:
https://cristianricharte6test.infura-ipfs.io/ipfs/QmTuAx44re7zJbZQDhkRJxTsWXoYjN2MvSj3DF8gn99WXq`

**This previous URI is the one you will need to add to the NFT when is minted.**
