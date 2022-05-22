<h1 align="center">
  <a href=""><img src="https://user-images.githubusercontent.com/15928266/116806917-ab0f8d80-ab62-11eb-8d34-962fdfe692a7.png" ></img></a>
</h1>
<p align="center"> 
  <a href=""><img src="https://img.shields.io/static/v1?label=php&message=%3E=7.3&color=green&style=flat&logo=php"></a>
  <a href=""><img src="https://img.shields.io/static/v1?label=Platform&message=Linux/Windows&color=orange&style=flat"></a>
  <a href=""><img src="https://img.shields.io/static/v1?label=License&message=MIT&color=blue&style=flat"></a>
   <a href=""><img src="https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg?style=flat"></a>
</p>

# SniperPhish-Docker
This repo is form maintaining docker release of [SniperPhish](https://sniperphish.com/). If you are installing SniperPhish in dcoker, use this repo. If youa are installing SniperPhish in it's original form, then visit https://github.com/GemGeorge/SniperPhish

## Docker Installation
1. Create the folders `mkdir -p  {uploads/attachments,uploads/timages,ht_files,hf_files}`
2. Create `db.php` file with informations about DB data
```
<?php
  $curr_db = "sniperphish";
  $conn = mysqli_connect("db","root","root",$curr_db);

  if (mysqli_connect_errno()) {
    die("DB connection failed!");
  }
?>
```


## More
* SniperPhish website: https://sniperphish.com/
* SniperPhish demo: https://demo.sniperphish.com/spear/

## Shoutouts
* [@sven-hash](https://github.com/sven-hash) for the docker implementation

## Come let's connect and collaborate
Join on our SniperPhish discord community to engage with us!
* Discord: https://sniperphish.com/discord/

## Donation
If this project help you 'Phish', you can give me a cup of coffee :) 

[![bitcoin](https://user-images.githubusercontent.com/15928266/124384822-9c318c80-dd05-11eb-948c-f0b9e697b740.png)](https://sniperphish.com/donate)
