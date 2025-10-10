# 2020 Brake
Racing sim Ebrake that has the same bolt pattern as the Moza!
<img width="1920" height="1080" alt="ebrake render" src="https://github.com/user-attachments/assets/d23dcd84-e73c-46c8-b06e-be4e0abb9cc6" />

## Why does this exist?
  I wanted an ebrake but all of the existing solutions either looked kind of boring or were extremely expensive (moza handbrake). 
# Build
## Assembly
  1. Press the handle and bottom piece onto the V slot aluminum
  <img width="221" height="783" alt="image" src="https://github.com/user-attachments/assets/1bb90092-f54b-44be-933a-7aae592ce22c" />
  
  2. Mark and drill an 8mm hole through the bottom of the aluminum where the top hole in the plastic is
  3. Wire the hall sensor and pro micro like this
     
  <img width="1000" height="735" alt="image" src="https://github.com/user-attachments/assets/4e3d7a5e-8dee-417c-9f4b-a0fc65ab530a" />
  
  5. Put the pro micro in here and secure it with tape or hot glue
     
  <img width="562" height="589" alt="image" src="https://github.com/user-attachments/assets/e71b39ee-f070-4ad6-a131-a07b5246c2e7" />
  
  7. Double sided tape the hall sensor here
     
  <img width="668" height="631" alt="image" src="https://github.com/user-attachments/assets/0e45d064-baa7-41d7-8003-08f3d7af7496" />
  
  9. Double sided tape the magnet here
      
  <img width="540" height="468" alt="image" src="https://github.com/user-attachments/assets/f5c97d46-7c00-4b75-9312-cb6be462a577" />
  
  11. Press fit bearings in each side of the base
      
  <img width="574" height="575" alt="image" src="https://github.com/user-attachments/assets/8d3fc3d9-644b-4082-9fd7-98bc588aceb7" />
  
  13. Put a rod through the bearings and shaft
  14. Attach the spring pivot like this
      
  <img width="615" height="628" alt="image" src="https://github.com/user-attachments/assets/b486ce8e-d4e1-477a-8398-2ea3e300e56d" />
  
  16. Insert the spring here
      
  <img width="851" height="562" alt="image" src="https://github.com/user-attachments/assets/de6db025-ec22-4f70-835e-626dc42d17e1" />
  
  18. Attach the side panels (optionally add the acrylic inserts)
      
  <img width="1107" height="771" alt="image" src="https://github.com/user-attachments/assets/23e24004-4f82-44e7-adac-fec4e67d459c" />


## Software
  ### https://github.com/ranenbg/Arduino-FFB-wheel
  1. Download the Xloader folder
  2. Run the .exe
  3. Click upload once you have selected the correct port

## BOM
|Item                                 |Quantity                                                 |Total price+Shipping|Use In project           |Item Source                                                                                                                                                                                                                                                                      |
|-------------------------------------|---------------------------------------------------------|--------------------|-------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Bearings 8x22x7mm                    |10pcs min purchase 2 used                                |$6.36               |Rotates the main pivot   |https://www.aliexpress.us/item/3256807915662185.html?spm=a2g0o.cart.0.0.5c7c38daZ6xG7Y&mp=1&pdp_npi=5%40dis%21USD%21USD%206.36%21USD%206.36%21%21USD%206.36%21%21%21%402103241117601158106153970edd5e%2112000043764624115%21ct%21US%214381910819%21%211%210&gatewayAdapt=glo2usa |
|Magnets 5x2mm                        |10pcs min purchase 1 used                                |$1.80               |Magnets                  |https://www.aliexpress.us/item/3256809772407336.html?spm=a2g0o.cart.0.0.5c7c38daZ6xG7Y&mp=1&pdp_npi=5%40dis%21USD%21USD%203.60%21USD%201.80%21%21USD%201.80%21%21%21%402103241117601158106153970edd5e%2112000050942051023%21ct%21US%214381910819%21%211%210&gatewayAdapt=glo2usa |
|KY-035 Hall Sensor                   |2pcs for 20 cents more these are not very reliable 1 used|$2.85               |Senses the halls (Magnet)|https://www.aliexpress.us/item/3256806209950505.html?spm=a2g0o.cart.0.0.5c7c38daZ6xG7Y&mp=1&pdp_npi=5%40dis%21USD%21USD%202.85%21USD%202.85%21%21USD%202.85%21%21%21%402103241117601158106153970edd5e%2112000040733161680%21ct%21US%214381910819%21%211%210&gatewayAdapt=glo2usa |
|Pro Micro usbc                       |1x                                                       |$7.05               |Controls everything      |https://www.aliexpress.us/item/3256806468327207.html?spm=a2g0o.cart.0.0.5c7c38daZ6xG7Y&mp=1&pdp_npi=5%40dis%21USD%21USD%207.05%21USD%207.05%21%21USD%207.05%21%21%21%402103241117601158106153970edd5e%2112000037934408603%21ct%21US%214381910819%21%211%210&gatewayAdapt=glo2usa |
|Spring Blue/whatever color 20x10x80mm|1x                                                       |$4.80               |Spring tension           |https://www.aliexpress.us/item/3256806244146198.html?spm=a2g0o.cart.0.0.5c7c38daZ6xG7Y&mp=1&pdp_npi=5%40dis%21USD%21USD%204.80%21USD%204.80%21%21USD%204.80%21%21%21%402103241117601158106153970edd5e%2112000037140711973%21ct%21US%214381910819%21%211%210&gatewayAdapt=glo2usa |
|Pins 8x40mm                          |10pcs min purchase 2 used                                |$6.78               |pivot points             |https://www.aliexpress.us/item/3256806373526334.html?spm=a2g0o.cart.0.0.5c7c38daZ6xG7Y&mp=1&pdp_npi=5%40dis%21USD%21USD%206.78%21USD%206.78%21%21USD%206.78%21%21%21%402103241117601158106153970edd5e%2112000037670585198%21ct%21US%214381910819%21%211%210&gatewayAdapt=glo2usa |
|2020 V slot 350mm                    |1x                                                       |$12.84              |shaft                    |https://www.aliexpress.us/item/3256803241979487.html?spm=a2g0o.cart.0.0.5c7c38daZ6xG7Y&mp=1&pdp_npi=5%40dis%21USD%21USD%2011.32%21USD%208.49%21%21USD%208.49%21%21%21%402103241117601158106153970edd5e%2112000025755955311%21ct%21US%214381910819%21%211%210&gatewayAdapt=glo2usa|
|Optional(Laser cut acrylic)          |1x                                                       |$8                  |COOOOL lookin sides      |My uni makerspace                                                                                                                                                                                                                                                                |
|Tax                                  |Its tax                                                  |$2.98               |Taxes                    |                                                                                                                                                                                                                                                                                 |
|TOTAL                                |                                                         |$53.46              |                         |                                                                                                                                                                                                                                                                                 |


