This is a fork of the core Tuya component. Edited some climate.py multipliers in order to make thermostats display correct values where the official integration shows the temperatures divided by 5.

I also made it possible to use this custom integration alongside the official one, so that if you have some thermostats that are shown correctly with the official one, you can still use it (and you will get all the devices and entities doubled). Anyways, if you only have thermostats that show the wrong values, this integration can fully replace the official one, since it allows you to manage any tuya integrated device just like the official one.

**In order to use this integration, follow these steps:**

**1.** Add the repository in your [HACS](https://hacs.xyz/):
/AlessandroTischer/tuya_climate_mult_edit

![image](https://github.com/AlessandroTischer/tuya_climate_mult_edit/assets/23379317/0972123a-cccd-4fa2-83a6-448a9c885fb2)

![image](https://github.com/AlessandroTischer/tuya_climate_mult_edit/assets/23379317/f123d2e6-26c5-4007-843e-bf9bbadc9f99)


**2.** Download in HACS "Tuya Climate Multiplier Edit".

**3.** In devices and services add integration "Tuya Climate Multiplier Edit".

![image](https://github.com/AlessandroTischer/tuya_climate_mult_edit/assets/23379317/814bf3c9-4678-4283-822d-a3b69550cbb8)


**4.** Configure the integration just [like you do with the official Tuya integration](https://www.home-assistant.io/integrations/tuya).

![image](https://github.com/AlessandroTischer/tuya_climate_mult_edit/assets/23379317/d7fab84e-a5b8-4938-87e4-836372a8a81b)


**5.** Done!

**BEFORE:**
![image](https://github.com/AlessandroTischer/tuya_climate_mult_edit/assets/23379317/485b6f12-00d1-4352-9b6c-cf227b823d84)

**AFTER:**
![image](https://github.com/AlessandroTischer/tuya_climate_mult_edit/assets/23379317/85b51635-4467-4265-bea4-8b7b1d974f97)

<img width="526" alt="image" src="https://github.com/AlessandroTischer/tuya_climate_mult_edit/assets/23379317/a7259ea5-5736-464e-bb9a-9d612483bfc1">
