# node-krowlr

## Installation

npm install krowlr

## Usage

    krowlr = require('krowlr');

    crawler = new krowlr.Crawler()
    crawler.add_url('http://mywesite/mypage')
    crawler.accepted_domains.push('www.myotherdomain')
    crawler.start()
