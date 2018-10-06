## Virgool Data
[![badge](https://img.shields.io/badge/version-1.0-blue.svg)](https://addons.mozilla.org/en-US/firefox/addon/shaparak-verifier/)  [![badge](https://img.shields.io/badge/license-MIT-yellow.svg)](asd)

package for getting data of posts and user profile from [virgool.io](https://virgool.io)
## Installation
    npm install virgool-data
## Usage

    const virgoolData = require("virgool-data");
    
    //get posts data
    virgoolData.getPosts().then(posts => console.log(posts));
    
    //get user data - username must be without "@"
    virgoolData.getProfile(username).then(user => console.log(user));
enjoy! 🤘
    

## Further help

visit [imohamad](http://imohamad.ml) or send e-mail: [mohamad.partizan@gmail.com](mailto:mohamad.partizan@gmail.com)
