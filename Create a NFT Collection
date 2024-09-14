/*
Assessment Requirements
1. Create a variable that can hold a number of NFT's. What type of variable might this be?
2. Create an object inside your mintNFT function that will hold the metadata for your NFTs. 
   The metadata values will be passed to the function as parameters. When the NFT is ready, 
   you will store it in the variable you created in step 1
3. Your listNFTs() function will print all of your NFTs metadata to the console (i.e. console.log("Name: " + someNFT.name))
4. For good measure, getTotalSupply() should return the number of NFT's you have created
*/

// create a variable to hold your NFT's
const NFTList = []

// this function will take in some values as parameters, create an
// NFT object using the parameters passed to it for its metadata,
// and store it in the variable above.
function mintNFT(_id, _name, _owner) {
  const NFT = {
    Id: _id,
    Name: _name,
    Owner: _owner,
  };

  NFTList.push(NFT);
}

// create a "loop" that will go through an "array" of NFT's
// and print their metadata with console.log()
function listNFTs() {
  for (const item of NFTList) {
    console.log(`\nID: ${item.Id}\nName: ${item.Name}\nOwner: ${item.Owner}`);
  }
}

// print the total number of NFTs we have minted to the console
function getTotalSupply() {
  console.log('\n' + NFTList.length)
  return NFTList.length
}

// call your functions below this line
mintNFT(12345, "Monkey NFT", "Genesis")
mintNFT(54321, "Doge NFT", "Genesis")
mintNFT(15243, "Cat NFT", "Genesis")
mintNFT(12243, "Hamburger NFT", "Genesis")
mintNFT(12243, "Hamburger NFT", "Genesis")
listNFTs()
getTotalSupply()
