# Log analyzer with Splunk


![Screenshot 2024-02-20 at 10 41 50](https://github.com/redjules/Log-analyzer/assets/106017493/e07049db-1ba8-4739-8bd2-7de332c9f722)

![Screenshot 2024-02-20 at 10 45 19](https://github.com/redjules/Log-analyzer/assets/106017493/1cf4add6-e6b1-4bcd-820d-b0e70af0dd03)

![Screenshot 2024-02-20 at 10 45 48](https://github.com/redjules/Log-analyzer/assets/106017493/3bc62977-a81a-49cc-916d-a01a724ecbf9)

![Screenshot 2024-02-20 at 10 47 03](https://github.com/redjules/Log-analyzer/assets/106017493/6c503712-0ca6-4922-99ad-4c96da3659df)

![Screenshot 2024-02-20 at 10 48 00](https://github.com/redjules/Log-analyzer/assets/106017493/2a37dc74-57b9-49ba-bf9d-5b8751178d1a)

![Screenshot 2024-02-20 at 10 48 53](https://github.com/redjules/Log-analyzer/assets/106017493/60b73dc7-a2ae-4800-a383-1cac41330863)

![Screenshot 2024-02-20 at 10 49 34](https://github.com/redjules/Log-analyzer/assets/106017493/94d2d57e-5382-41c3-8d57-c94ef8cad901)

![Screenshot 2024-02-20 at 10 50 24](https://github.com/redjules/Log-analyzer/assets/106017493/01add557-b2c0-4ee5-869b-dec40480fa90)

we go to the Splunk website and download the right version:

![Screenshot 2024-02-20 at 10 52 54](https://github.com/redjules/Log-analyzer/assets/106017493/2d1245f8-d291-430f-b202-8ab01bf1f9d7)

![Screenshot 2024-02-20 at 10 57 39](https://github.com/redjules/Log-analyzer/assets/106017493/2b2f9e5c-f3c1-415a-b99d-1fb49f1bc0ea)

# Demo

We go to Settings and Data Inputs:

![Screenshot 2024-02-20 at 10 58 33](https://github.com/redjules/Log-analyzer/assets/106017493/79d9d1a4-67ec-4da0-bc98-17df08ec304d)

![Screenshot 2024-02-20 at 10 59 08](https://github.com/redjules/Log-analyzer/assets/106017493/80b5d72b-d56a-413e-a460-50bd96fed5bf)

we click SettingsSync:

![Screenshot 2024-02-20 at 12 18 07](https://github.com/redjules/Log-analyzer/assets/106017493/e2d20a63-2b8a-4c8d-8ea7-cae7a66e1743)

![Screenshot 2024-02-20 at 12 18 53](https://github.com/redjules/Log-analyzer/assets/106017493/51c51884-2d2f-4fb1-9179-1aa96f6b438d)

![Screenshot 2024-02-20 at 12 21 34](https://github.com/redjules/Log-analyzer/assets/106017493/7d016780-8953-48f7-bd22-640afe3588b8)

![Screenshot 2024-02-20 at 12 21 55](https://github.com/redjules/Log-analyzer/assets/106017493/7eddf812-260a-4af9-a6d0-07420a2fe9b0)

![Screenshot 2024-02-20 at 12 25 21](https://github.com/redjules/Log-analyzer/assets/106017493/754ff001-ad73-431f-9a98-b929bd7a1191)

we go to Settings and Forwarding and receiving:

![Screenshot 2024-02-20 at 12 27 40](https://github.com/redjules/Log-analyzer/assets/106017493/a566b849-5a9f-4a03-8ffb-62f78f4e87b5)

![Screenshot 2024-02-20 at 12 28 02](https://github.com/redjules/Log-analyzer/assets/106017493/1ff16a0b-c9bf-4f25-a571-e4bc6706468f)

![Screenshot 2024-02-20 at 12 28 37](https://github.com/redjules/Log-analyzer/assets/106017493/fbfe8d15-9eae-4f2d-9474-edb9b5ed565a)

we create a new receiving port:

![Screenshot 2024-02-20 at 12 29 45](https://github.com/redjules/Log-analyzer/assets/106017493/d421a10b-e9e2-41aa-9aae-f62e2acc5548)

go to settings indexes:

![Screenshot 2024-02-20 at 12 34 55](https://github.com/redjules/Log-analyzer/assets/106017493/2c15be71-f92d-436e-87fb-507e4490dddc)

we create a Dashboard:

![Screenshot 2024-02-20 at 12 36 03](https://github.com/redjules/Log-analyzer/assets/106017493/db6a8aa2-b878-4456-93e8-017925fabed5)

![Screenshot 2024-02-20 at 12 38 27](https://github.com/redjules/Log-analyzer/assets/106017493/c305116f-37d5-4935-8e19-3f98ac164b64)

we go to reports:

![Screenshot 2024-02-20 at 12 45 53](https://github.com/redjules/Log-analyzer/assets/106017493/71eb59dd-7f48-47af-b97d-9261afb7cb8c)

we will add the report to the previous Dashboard:

![Screenshot 2024-02-20 at 12 47 57](https://github.com/redjules/Log-analyzer/assets/106017493/a9772800-af72-4924-9dbd-9e2f0a4735a5)

we check the Health Status:

![Screenshot 2024-02-20 at 12 48 47](https://github.com/redjules/Log-analyzer/assets/106017493/aff79da4-31ef-46b3-8e51-d8a21660be70)

# Bonus


Example of log (CISCO PIX log):

![Screenshot 2024-02-19 at 13 32 32](https://github.com/redjules/Log-analyzer/assets/106017493/64cdad12-a4b4-4aee-b464-77d3b26d5a4d)

The first step is to reduce the noise. For example, this text repeats itself:

![Screenshot 2024-02-19 at 13 33 30](https://github.com/redjules/Log-analyzer/assets/106017493/267beafa-6a99-4929-a8c4-e1e7e3d02e76)

we replace the repeated text with nothing:

![Screenshot 2024-02-19 at 13 33 48](https://github.com/redjules/Log-analyzer/assets/106017493/ef5f4020-08fd-43be-aa94-0216464a6806)


also this section repeats:

![Screenshot 2024-02-19 at 13 34 20](https://github.com/redjules/Log-analyzer/assets/106017493/9afe7f02-7f61-4467-8aa6-d7112ee10cde)

we replace the repeated text with nothing:

![Screenshot 2024-02-19 at 13 35 04](https://github.com/redjules/Log-analyzer/assets/106017493/586964f3-0659-4761-a82b-d3016e1a00f7)

we separate the text and read line by line and look at the time:

![Screenshot 2024-02-19 at 13 35 52](https://github.com/redjules/Log-analyzer/assets/106017493/30214fdf-4828-4c50-a614-0f90d03df311)


if it was an automated tool, it would be a rapid succession like several requests on the same second.

This is a manual attack and he is trying different approaches:

![Screenshot 2024-02-19 at 13 40 37](https://github.com/redjules/Log-analyzer/assets/106017493/bc97c871-151a-4521-91c6-6b18b86b1440)


Here the attacker is trying to download a file from a remote site:

![Screenshot 2024-02-19 at 13 41 39](https://github.com/redjules/Log-analyzer/assets/106017493/6fa83ef7-1c53-47b0-89d5-108248c613cb)

and it's working:

![Screenshot 2024-02-19 at 13 42 01](https://github.com/redjules/Log-analyzer/assets/106017493/5fe8b482-855c-4faf-b15b-d006ac79074c)

he continues the attack:

![Screenshot 2024-02-19 at 13 42 56](https://github.com/redjules/Log-analyzer/assets/106017493/0a3bffe4-855e-4f2d-a352-c7174524d0fa)

here he steals the word press credentials:

![Screenshot 2024-02-19 at 13 43 30](https://github.com/redjules/Log-analyzer/assets/106017493/e3e5f47b-cc59-4697-ac73-712a01f9b60a)

and found an old password:

![Screenshot 2024-02-19 at 13 44 22](https://github.com/redjules/Log-analyzer/assets/106017493/1b0086b0-cb1b-4acb-9950-8744f79cacdf)
