# Lesson 8: HTML / Javascript Fund Me (Full Stack / Front End)

Lesson 8 from the Web3, Full Stack Solidity, Smart Contract & Blockchain - Beginner to Expert ULTIMATE 
Course | Javascript Edition:
https://github.com/smartcontractkit/full-blockchain-solidity-course-js#lesson-8-html--javascript-fund-me-full-stack--front-end

Official code at:
https://github.com/PatrickAlphaC/html-fund-me-fcc

## Notes

* using **ethers** version 6.9.0 which is incompatible with version 5.6.0 used in the course
  * `ethers.providers.Web3Provider` was replaced with `ethers.BrowserProvider` 
  * `provider.getSigner()` returns a Promise and it needs `await`
  * `ethers.utils.parseEther` was replaced with `ethers.parseEther`
    * similarly `ethers.utils.formatEther` was replaced with `ethers.formatEther`
  * **ethers** migration guide from 5 to 6: https://docs.ethers.org/v6/migrating/