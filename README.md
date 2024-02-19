# Log analyzer for Attacks:

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
