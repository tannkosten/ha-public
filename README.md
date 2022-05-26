# Home-Assistant!

## My setup

I run Home Assistant as a virtual machine on a Proxmox host

I monitor my power usage with Tibber Pulse. It's connected to the HAN port of my smart meter.

I also use Nabu Casa Cloud, and most integrations work through that solution.

I have 3 touchscreen devices around my apartment for easy access to controlling lights, and more.

For my living room:
 * [Samsung Galaxy Tab A 10.1 (2019)](https://www.amazon.com/Samsung-Galaxy-10-1-Tablet-Black/dp/B07Q5VM8ZD/ref=sr_1_4?keywords=samsung+galaxy+tab+a+10.1+2019&qid=1567840723&s=gateway&sr=8-4)
 * [Koala Mount 2.0](https://www.dockem.com/Koala-Mount-2-0-p/ko2.htm)
 * Running [Fully Kiosk Browser](https://www.ozerov.de/fully-kiosk-browser/) to show the HA Dashboard

 For my entrance:
  * [Raspberry Pi 7" Touch Screen](https://www.amazon.com/Raspberry-Pi-7-Touchscreen-Display/dp/B0153R2A9I/ref=sr_1_3?keywords=raspberry+pi+touch&qid=1567841015&s=gateway&sr=8-3)
  * [Raspberry Pi 3A+](https://www.amazon.com/Raspberry-Pi-3-Computer-Board/dp/B07KKBCXLY/ref=sr_1_3?keywords=raspberry+pi+3a&qid=1567841044&s=gateway&sr=8-3) running Raspbian

For my bedroom:
  * [Huawei MediaPad T3 10](https://www.amazon.com/Huawei-MediaPad-Android-Aluminum-International/dp/B07CNLYK6S/ref=sr_1_1?keywords=Huawei+mediapad+T3&qid=1567841109&s=gateway&sr=8-1)
  * [Vogels TMS 1030 Flexi Pack](https://www.amazon.com/Vogels-Tablet-Mount-Universal-Adjustable/dp/B00LCCWRAQ/ref=sr_1_2?keywords=vogels+tms+1030&qid=1567841146&s=gateway&sr=8-2)
  * Running [Fully Kiosk Browser](https://www.ozerov.de/fully-kiosk-browser/) to show the HA Dashboard


My lights:
  * All my lights are [IKEA Trådfri](https://www.ikea.com/us/en/search/?query=trådfri) connected to the IKEA Trådfri Gateway

My heating:
  * I currently have 3 [Mill Panelovn with WiFi](https://www.millheat.com/mill-wifi)

Temperatures:
  * [Netatmo Weatherstation](https://www.amazon.com/Netatmo-NWS01-Weather-Station/dp/B0095HVAKS/ref=sr_1_4?keywords=netatmo&qid=1567841915&s=gateway&sr=8-4)

Smoke detectors (not added, because apparently they don't allow new developer accounts for API access):
  * [Nest Protect Smoke alarm (battery)](https://www.amazon.com/S3000BWES-Protect-Carbon-Monoxide-Battery/dp/B00XV1RCRY/ref=sxin_1_ac_d_rm?ac_md=0-0-bmVzdCBwcm90ZWN0-ac_d_rm&keywords=nest+protect&pd_rd_i=B00XV1RCRY&pd_rd_r=76ed8a44-39d8-4f00-9c85-ef1a2e62f9fc&pd_rd_w=crt02&pd_rd_wg=yrsHj&pf_rd_p=404c4843-2c96-4d0d-a5fe-2b0598693e61&pf_rd_r=PJRQ2329KNFJJW14S8E5&qid=1567842390&s=gateway)

Vacuum cleaner:
  * [Xiaomi Roborock S6](https://www.amazon.com/Roborock-S6-Adaptive-Selective-Cleaning/dp/B07RLRWWPJ/ref=sr_1_1?keywords=xiaomi+roborock+s6&qid=1568017447&s=gateway&sr=8-1) - mine is white, but no matter.
  * Explanation below is for android. iPhone should still store the token in an sqlite file under the storage for the Mi Home app.
  * In order to get the token required for HA to talk with the Xiaomi vacuum cleaner, I had to install a Spanish app from npirtube.com/mi-home-app. Log in, and it will create a file called devices.ini, which contained the token I needed.
  * After that you can remove this app. I installed it on a spare phone.
  * If you're looking for it in my config files, it's called Deku.

Blinds:
  * [IKEA Fyrtur](https://www.ikea.com/no/no/p/fyrtur-lystett-rullegardin-tradlos-batteridrevet-gra-20408178/)
