# SimplySplit
This is my low profile split keyboard. I made this because I really wanted to make a keyboard but also didnt want it to be too simple. This is why I made a bluetooth split keyboard. Because of it's small form factor it can "fit" into your pocket. This is useful as I really enjoy using my old RasPi on the go and a bt keyboard is realy useful.

## Images
![Final Render Front](https://github.com/Enzo13221/SimplySplit/blob/main/Images/FinalRender.PNG?raw=true)

(If you noticed that the connector for the Battery is being clipped by the top plate I decided to not use the connector but leave the footprint there as an option)

<img width="780" height="530" alt="image" src="https://github.com/user-attachments/assets/b12b9da3-0b11-4c25-9df3-070d53a47a3a" />


<img width="1602" height="765" alt="image" src="https://github.com/user-attachments/assets/38e6fadd-5d70-4792-b91d-bb4da4c24d33" />


<img width="1918" height="938" alt="image" src="https://github.com/user-attachments/assets/9e862417-6b98-486a-ac5b-63b5f2d21f95" />

# Firmware can be found here

https://github.com/Enzo13221/zmk-config/tree/main 

# BOM
| Item            | Description        | Quantity | Unit price | Total price | Price + tax | Running total | Link       |
| --------------- | ------------------ | -------- | ---------- | ----------- | ----------- | ------------- | ---------- |
| Keycaps         | CFX, White         | 40       | $0.33      | $13.07      | $14.77      | $14.77        | [AliExpress](https://www.aliexpress.us/item/3256810199199272.html?spm=a2g0o.detail.pcDetailBottomMoreOtherSeller.23.51667HnN7HnNaF&gps-id=pcDetailBottomMoreOtherSeller&scm=1007.40050.354490.0&scm_id=1007.40050.354490.0&scm-url=1007.40050.354490.0&pvid=384d1b43-ab82-45ca-9332-caee7cd0b6ae&_t=gps-id:pcDetailBottomMoreOtherSeller,scm-url:1007.40050.354490.0,pvid:384d1b43-ab82-45ca-9332-caee7cd0b6ae,tpp_buckets:668%232846%238107%231934&pdp_ext_f=%7B"order"%3A"22"%2C"eval"%3A"1"%2C"sceneId"%3A"30050"%2C"fromPage"%3A"recommend"%7D&pdp_npi=6%40dis%21USD%219.70%210.99%21%21%219.70%210.99%21%402101ea8c17712834864303402ea509%2112000052228852471%21rec%21US%21%21ABXZ%211%210%21n_tag%3A-29910%3Bd%3A5299cee1%3Bm03_new_user%3A-29895%3BpisId%3A5000000197847450&utparam-url=scene%3ApcDetailBottomMoreOtherSeller%7Cquery_from%3A%7Cx_object_id%3A1005010385514024%7C_p_origin_prod%3A) |
| Switches        | Choc v1 brown      | 40       | $0.74      | $29.34      | $33.15      | $47.92        | [AliExpress](https://www.aliexpress.us/item/3256806486085031.html?spm=a2g0o.productlist.main.10.41f013a7iUGzO1&algo_pvid=29c271cb-d14e-451b-9722-29b87397267c&algo_exp_id=29c271cb-d14e-451b-9722-29b87397267c-9&pdp_ext_f=%7B"order"%3A"97"%2C"eval"%3A"1"%2C"fromPage"%3A"search"%7D&pdp_npi=6%40dis%21USD%216.92%216.92%21%21%2147.48%2147.48%21%402103128817712830262832957ee54e%2112000037979106609%21sea%21US%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A5299cee1%3Bm03_new_user%3A-29895&curPageLogUid=fiXY8vuLofNm&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005006672399783%7C_p_origin_prod%3A) |
| Batteries       | 3.7V 200mAh        | 2        | $2.84      | $5.68       | $6.42       | $54.34        | [AliExpress](https://www.aliexpress.us/item/2251832643018973.html?spm=a2g0o.detail.pcDetailTopMoreOtherSeller.4.2706ETrhETrhlN&gps-id=pcDetailTopMoreOtherSeller&scm=1007.40050.354490.0&scm_id=1007.40050.354490.0&scm-url=1007.40050.354490.0&pvid=02574686-c7bf-467c-94c4-5f7aa57118c0&_t=gps-id:pcDetailTopMoreOtherSeller,scm-url:1007.40050.354490.0,pvid:02574686-c7bf-467c-94c4-5f7aa57118c0,tpp_buckets:668%232846%238111%231996&isseo=y&pdp_ext_f=%7B"order"%3A"116"%2C"eval"%3A"1"%2C"sceneId"%3A"30050"%2C"fromPage"%3A"recommend"%7D&pdp_npi=6%40dis%21USD%212.84%212.84%21%21%212.84%212.84%21%40210328df17712797568823146e484c%2112000040902843221%21rec%21US%21%21ABX%211%210%21n_tag%3A-29910%3Bd%3A5299cee1%3Bm03_new_user%3A-29895&utparam-url=scene%3ApcDetailTopMoreOtherSeller%7Cquery_from%3A%7Cx_object_id%3A32829333725%7C_p_origin_prod%3A)  |
| Molex Connector | WM1742-ND          | 2        | $0.45      | $0.90       | $1.02       | $55.36        | [DigiKey](https://www.digikey.ca/en/products/detail/molex/0530480210/242864)    |
| Resistor        | MFR-25FBF52-806K   | 2        | $0.14      | $0.28       | $0.32       | $55.68        | [DigiKey](https://www.digikey.ca/en/products/detail/yageo/MFR-25FBF52-806K/13696)    |
| Resistor        | HVR3700002004FR500 | 2        | $0.58      | $1.16       | $1.31       | $56.99        | [DigiKey](https://www.digikey.ca/en/products/detail/vishay-beyschlag-draloric-bc-components/HVR3700002004FR500/719532)    |
| Diode           | 1N4148W            | 45       | $0.19      | $8.55       | $9.66       | $66.65        | [DigiKey](https://www.digikey.ca/en/products/detail/smc-diode-solutions/1N4148W/6022450)   |
| PCB+Top plate   | See attached image | 1        | $11.55     | $36.88      | $41.67      | $108.32       | N/A        |
| Bolts           | M3x20mm            | 20       | $0.18      | $3.54       | $4.00       | $112.32       | [AliExpress](https://www.aliexpress.us/item/3256807895942562.html?spm=a2g0o.productlist.main.17.5ab26bba9gkouK&algo_pvid=9569f8b8-50c7-4709-bb61-aa0e50691b59&algo_exp_id=9569f8b8-50c7-4709-bb61-aa0e50691b59-16&pdp_ext_f=%7B"order"%3A"815"%2C"eval"%3A"1"%2C"fromPage"%3A"search"%7D&pdp_npi=6%40dis%21USD%211.64%210.99%21%21%211.64%210.99%21%402101e81117712966712334141eaf0b%2112000043609478511%21sea%21US%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A5299cee1%3Bm03_new_user%3A-29895%3BpisId%3A5000000198352206&curPageLogUid=pqj3T9RK0P7g&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005008082257314%7C_p_origin_prod%3A) |
| Spacers         | M3x6mmx1mm         | 200      | $0.02      | $2.21       | $2.50       | $114.82       | [AliExpress](https://www.aliexpress.us/item/3256807407806741.html?spm=a2g0o.productlist.main.1.65091593KQNbL0&algo_pvid=b8acf6cb-9c4f-45eb-a65f-3304e9bf4beb&algo_exp_id=b8acf6cb-9c4f-45eb-a65f-3304e9bf4beb-0&pdp_ext_f=%7B"order"%3A"32"%2C"eval"%3A"1"%2C"fromPage"%3A"search"%7D&pdp_npi=6%40dis%21USD%212.21%210.99%21%21%2115.17%216.80%21%402103212b17712919601903092e4830%2112000041427681765%21sea%21US%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A5299cee1%3Bm03_new_user%3A-29895%3BpisId%3A5000000198352206&curPageLogUid=T75qFSRd0QTp&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007594121493%7C_p_origin_prod%3A) |
