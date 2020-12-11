## Obstacle Avoiding Rover (code name *Nala*)

A mini rover which can detect and avoid any obstacle using the ultrosonic sensor which sits on top of a servo motor. 

![output](https://lh3.googleusercontent.com/pw/ACtC-3c3C0kW0H2E_PKvKNevR4AVeJqnf3NxOqwspM69sPE5tgZW1W7tZiDU49ubpB-yvRKahRvVDF8gQSjCQGEDrbM5HYXuHTB-Ko50Lnp01SsC4JrWyZH1wi-roFGEO4NOGy964z7Ri4ejEhPUEkTaA4K8-g=w1186-h889-no?authuser=0)

### Disclaimer 

*There is nothing new in this repository. Most of the work is copied from someone else. Its just a work of stictching everything together* 

## Components

 - Arduino Uno - https://amzn.to/3n8KCkk
 - Motor Driver Shield - https://amzn.to/30Z9ijj
 - TT Gear Motor and wheels set - https://amzn.to/31WSD0Z (Buy some extra pair. Its very likely that you may break for the first time, becuase I did)
 - Servo Motor - https://amzn.to/2IAigNH
 - Ultrasonic Sensor - https://amzn.to/33fwrQa
 - 18650 Li-on Battery (2x) - https://amzn.to/3hQJwXk
 - 18650 Battery Holder - https://amzn.to/33iY4b3
 - Male and Female Jumper wire - https://amzn.to/2MmRjOE
 - Acrylic Sheet - https://amzn.to/39Fi0ZY
 - DC Power Switch - https://amzn.to/313hgKf
 - Screws with various sizes, trust me it will require - https://amzn.to/2BOmt04

## Prerequisite 

 - Mini Hacksaw (https://amzn.to/2Dkb0FM) # to cut the acrylic sheet
 - Screwdriver
 - Soldering iron
 - Fevi quick
 - Drilling tool, to puch holes in the sheet - https://amzn.to/3jXmEYb this would do. 
 - Arduino IDE which comes in all flavour including Windows app - https://bit.ly/3k2wTun

## Build

* Cut acrylic sheet into 14 * 9 cm (use Hacksaw)

![Base](https://lh3.googleusercontent.com/AGQvQ10h96-1t8rdvXWaM_IPfj_FevaIVqwzse_5afroegguCRf5OUabw-wNOnR2RjG5mLWG8djyIeaQaasjoIGWPGDoSe4Px6Hh5MR3t2DKcD6BXaljkNAxXCBcKSmRJGNpMpKPERnIPG-pjM-5O8uPoZr362iWIM9BQEkp5TPXej7NEZrH42btimY8FvoDkwvUQjZbADq_tJUfoO52fLBhNdSXFIETaKlWC2gOBWnYpTsZT1zpO7kRCRjkxqniuQKLtwsffHA7f3WubdntnmXvkeujHf14913F8ZA4h4IZjWqhfRdPX7o_P93CGtGc3MhDPlrfKC6wW95aCAm_xIDuMUnaNW-lwzpPCR8umxjXjPiTwgLuHS7xkXlSbfu5M_2CushTRqfQv3Wm6akIkKDmsq9_Q99itqHnaa8JkFg-yXg4EC7RI90oIqRQiH5EqfH9DYoctyqxNs8J1y4JqrXpho2_hQwjy8mJlsjbbNiSLXu6Shm31u3q99OuTQnj8V-F25PBUAeybSKDwifYX1bFCfAkuN_WaO5KcXdkq31q-JYzM5QEWKB-Z-ehJahFTXHGHqsGtzh_V_H_7UAG5e8ztGRE2Dmm9W3Qnp6egTNjk39eD0K46GDsxNr0AfpaY3nZV1h6_oLi9guNHtkeTvcG9z5nihXt7DtmnTw-nrqXuocTN40p8pYjfYvGZg=w703-h937-no?authuser=0)

![Sensor](https://lh3.googleusercontent.com/HsQE_J4419KR5IUZPHFLo0V4lx4rUHBzneXZYG_iE4eV0tRfzTzqpItKo36lRO-6X2fHNk40uSsqj0BU9kdGMjoj5pUHJR9IQm_VmVGUofAMEDKjBHGew6Sa9WnczHp_wzIjdos4vqWQedOeyE7P0I8cqihl7lyCWjRb6jX25NOMP3K66CaBIVNaT6giZM4W5wSwvtWQRUFKWFCRE2e6YOIM-aZHudNPOL2rya9XBWFisVwuapmeiF0VaGZqxh6Mrc23FnK_Ny4zb7Ix4FFXMmyDE8O6f7stWey9VcMM-WtUSUbtfbCSftyFOWFz3p8YNZIZGgqMCGpw2jCy9cjjJEFMLmuufTsGfiEf_HHzlZpXEk6IErSPcXgyoEpmsMmobTIzIkFP5NOpt1Ahu-JrEeTtwZ8H9AzygqeJL17Bk4M35y3DPGRRzRh5Q1dGea2Q_pra22_haWipFAJpI36Ei2cAtfxkmgEpQzu-tR8_4bMebT5evLd99DGPcPwSRMzw9MkTK3cfNQHcGxMBcBwBH2fruQIdHV3hntmDt5CXPW9kGENNPaVIF_FZhmOgF60w6LF-ATFpVTM4I2loK_Ou6C5yNU1WUE53OlUNfuKNEoMq7BHPwOlBF12Oxb_q9g7PUXNHhovGoATGmKkoxdMC4p58slCfiHpHYBC93YPC9lot3WRQO3oBSJSEvYTrwA=w703-h937-no?authuser=0)

![With sensor attached](https://lh3.googleusercontent.com/Kw0C3jzl6YK7ZYk-TNzF-zZrUgXfKCVlGh-eYCA-e9LqlTeUoFS3WKSUOiyU-rw555IdKRjdRVMDRVbiYqNes81q_IPMjj0XX3uM7g6cjEuKDJWu-7zvLFU4b0eTNx85wDFbBfFiApVhH-03dU7FAEhrw-rhZa1qreXJ-3lSkvN5qSR9HOjeRWX6EDWGqxA6iSOvFVINJGSm2JOPKncqLFXNG-g91P1QJcaMDx03b-n224JTDB0eKFnYFDl5h9HSqEuUdMIq1fxr_iYIvH5dAQdo563tNHREUB5IJSf9Y-G5tY-dAEZfJnBLBBwNWZfgT3MuA6s7xg8JOqmXqydlbUrzbFXlB1kkM0ZJKey3NXw32vRhweVxxDgaH0QCLterkrsWqEwctvjRnAj3UaMi1vw6KgZEQ2WD79NYFYoLViivXF5cj7Xkw0-9GQIn9MfdgezpVnxiuIKF0wJUYMFDRoHwibv_ZGnleB7si5QETLytnfY-dYqYmlB1owh68ZNFlXVUFbbrqsDK6Rd6A2Y9x9xTAzCaIFhRReBDclZgUGybSQCd_8o-LhSPIqAGKuaAzpZpWSHCGksQbnA33mdJVyHMCFTJ2ynn8-jiUH6S271CYRgX3GXdO58Ip1vKLp9bkVVfR8ANTh2w6JOfrwSu2ia9x64Nc8l_WQH3GioyVivOInBJJXh5vejUFuWCVg=w703-h937-no?authuser=0)

## How Ultrasonic Sensor work ? 

![Ultrasonic Sensor](https://lastminuteengineers.com/wp-content/uploads/arduino/HC-SR04-Ultrasonic-Sensor-Working-Echo-reflected-from-Obstacle.gif)

## Upload the code

 - Connect the USB cable to the interface on the Aurdino board. 
 - Spin up the Aurdino SDE
   - Make sure you selected the right COM port to upload the code Tools -> Port -> COM 2 or whatever
 - Click Upload (icon ->)
 - Adding the relevent libraries are on the code description.

![Upload code image](https://lh3.googleusercontent.com/UfcBFNIHOXEE3QDkWXSngwDeaWiLPFYZbVuiti0yt_1AXtpWl-pAQWQYaETNy1OCMrYPIr5qM0WHHLwpsF-CMck-0fOIQ1C3DtgvSG9N779IQ_qpra8II-uOBmSK2CqCk84LKkwIBrmbML2zFjNWgu2nz6-gUdsBPzhYi3pevs-YrTwDku-4NuRCR-gADIGN-nyz1zw8flZ_7L6ALqg63GMLxUlFvHS8bEEKFV-SPEokYfac-qxL9XvPzn1hEFwIVqIz-FT9NY2CVZbRUr5yLM1H8WCERJJGMPwC7LDayFuy7qvJ0T0HiVWXibwg6c0IZ8eBGIgMstf-vmuYgIq3-Llj91_kELvhNgwd__QrisPgKJes5K5eTRujEo8pQ179Q_22s9PdvoBgoXBDJIJtfE8U5BbagVGyFCMJjjIGfcZ-f8tyE0ynlm-nBh5jQUVlOcbhMQ0nDz5FN2yJke7Pff2tjx94CuV3-5AnZCw5E72qHMsT2i_40iKxuSOwg12QLv0VAGhgLGYOc9cGJmuec3s5CW-TpCxq9shT1SFvPtfAuJ_GF1bUgo9n8jcCn064Xfpt-g9MMlm-MBJ7bcxg2U1EpB1QjTQn3zU3xgtqr9kDylozamsDpo9UPlINGfNGHnQgLsSaYVsErr0kq5RpqminGysV_9k3H0ME6VUOmwwVZKsAPf_d6cqjRvlATg=w1255-h937-no?authuser=0)

## Final output 

(click to see the video)

[![Mini Rover](https://lh3.googleusercontent.com/pw/ACtC-3c3C0kW0H2E_PKvKNevR4AVeJqnf3NxOqwspM69sPE5tgZW1W7tZiDU49ubpB-yvRKahRvVDF8gQSjCQGEDrbM5HYXuHTB-Ko50Lnp01SsC4JrWyZH1wi-roFGEO4NOGy964z7Ri4ejEhPUEkTaA4K8-g=w1186-h889-no?authuser=0)](https://www.youtube.com/watch?v=1GMyHdt2BrA "Mini Rover")

## Next ?

Make the turns realistic so that it does not have to stop - reverse - look - procced. 

