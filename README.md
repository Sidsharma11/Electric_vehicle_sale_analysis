# Electric_vehicle_sale_analysis

**Steps Peformed:**

**Step-1: In the sale_by_state table,updated the State column by changing 'Andaman & Nicobar' to 'Andaman & Nicobar island'**

![Screenshot 2024-07-26 104136](https://github.com/user-attachments/assets/1ebc51e6-08ad-4a2a-afe6-a88c318af147)


---

**Q-1)List the top 3 and bottom 3 makers for the fiscal years 2023 and 2024 in terms of the number of 2-wheelers sold.**

![Screenshot 2024-07-26 104548](https://github.com/user-attachments/assets/cd2b7c8d-9ba8-4a6c-8054-90b425caf1e4)
![Screenshot 2024-07-26 104648](https://github.com/user-attachments/assets/665f47b0-9ed0-41f7-a51d-a1b3e2c1aa0d)

![Screenshot 2024-07-26 104851](https://github.com/user-attachments/assets/86cc38b1-436a-416f-b066-1b583b7d96cc)
![Screenshot 2024-07-26 104915](https://github.com/user-attachments/assets/faf37f26-a2c5-41ae-8cc9-11daa6c61126)

---

**Q-2)ldentify the top 5 states with the highest penetration rate in 2-wheeler and 4-wheeler EV sales in FY 2024.**

![Screenshot 2024-07-26 105459](https://github.com/user-attachments/assets/d70041a4-2d60-482f-9e2b-1ab11e472466)
![Screenshot 2024-07-26 105515](https://github.com/user-attachments/assets/96e0982f-d73b-4e5b-be5b-254f8ffa219c)


![Screenshot 2024-07-26 105542](https://github.com/user-attachments/assets/eef8d855-193f-4b82-b13b-823d130cbe27)

***

**Q-3)List the states with negative penetration (decline) in EV sales from 2022 to 2024?**

Created views pct_sale_2022 and pct_sale_2024


![Screenshot 2024-07-26 113156](https://github.com/user-attachments/assets/7218aa66-cbbd-4ee2-93e6-b7597193fea9)
![Screenshot 2024-07-26 113305](https://github.com/user-attachments/assets/a99c2cb8-7ac4-4a45-b68c-c8ac3402f0fa)

![Screenshot 2024-07-26 121054](https://github.com/user-attachments/assets/29876281-ea9b-4d9b-beb1-4599cec8a32e)
![Screenshot 2024-07-26 121106](https://github.com/user-attachments/assets/001594d9-38d5-4e21-835a-f97ed32ede3e)

***

**Q-4)What are the quarterly trends based on sales volume for the top 5 EV makers (4-wheelers) from 2022 to 2024?**

Created temporary table for the sale in  Q1,Q2,Q3 and Q4

![Screenshot 2024-07-26 174032](https://github.com/user-attachments/assets/094d761e-1e5c-4fbb-ac2e-b749dcb6bc3e)

![Screenshot 2024-07-26 174050](https://github.com/user-attachments/assets/b405648a-3165-4274-9991-ec4b385bf302)

![Screenshot 2024-07-26 174059](https://github.com/user-attachments/assets/99999275-c120-4683-a78d-3df29022633e)

![Screenshot 2024-07-26 174109](https://github.com/user-attachments/assets/674ea95f-6541-43c5-915b-a5ac7de759f9)

![Screenshot 2024-07-26 174127](https://github.com/user-attachments/assets/4d909f0d-c7da-4b10-b096-ff8dc5afa424)

![Screenshot 2024-07-26 174147](https://github.com/user-attachments/assets/658073af-cdb6-42c0-9405-dc719acf2dda)

![Screenshot 2024-07-26 174234](https://github.com/user-attachments/assets/a2810e56-ee75-46de-9b1b-1302a2bcb206)

Similary , for the fiscal_year 2023

![Screenshot 2024-07-26 174955](https://github.com/user-attachments/assets/df2d1114-e1ee-43f4-9d1a-6429c174a7fe)

for the fiscal_year 2024

![Screenshot 2024-07-26 175311](https://github.com/user-attachments/assets/641d15f6-f995-4110-9d26-b579cdc3233d)

***

**Q-5)How do the EV sales and penetration rates in Delhi compare to Karnataka for 2024?**

Used view 'electric_vehicle_sale_pct_2024'


![Screenshot 2024-07-26 175958](https://github.com/user-attachments/assets/f39d7e31-0cf4-4984-a162-ff8917d2c06e)
![Screenshot 2024-07-26 180004](https://github.com/user-attachments/assets/4f86a50b-602a-4aec-960a-f404cf60cfc6)

***

**Q-6) Listdown the compounded annual growth rate (CAGR) in 4-wheeler units for the top 5 makers from 2022 to 2024.**

![Screenshot 2024-07-26 183046](https://github.com/user-attachments/assets/89fd3100-c32e-49eb-807a-5ad1057e665d)
![Screenshot 2024-07-26 183058](https://github.com/user-attachments/assets/c5fc4206-d790-4919-9deb-307729e1ef36)
![Screenshot 2024-07-26 183110](https://github.com/user-attachments/assets/5eb45990-f737-409e-8110-9b9be42c640e)
![Screenshot 2024-07-26 183124](https://github.com/user-attachments/assets/31a77517-b25a-4453-b718-e4b49ce26628)

***

**Q-7)Listdown the top 10 states that had the highest compounded annual growth rate (CAGR) from 2022 to 2024 in total vehicles sold.**

![Screenshot 2024-07-26 191244](https://github.com/user-attachments/assets/3547df1f-7d15-49af-9f4a-4864bbf5618e)

![Screenshot 2024-07-26 191251](https://github.com/user-attachments/assets/200920b2-420c-49b7-a3dc-eba9df22b3ea)

![Screenshot 2024-07-26 191306](https://github.com/user-attachments/assets/7846975e-9955-4fc3-b924-e0439e75f527)

![Screenshot 2024-07-26 191324](https://github.com/user-attachments/assets/536121aa-f837-4cd4-a2da-8502c0c8706a)

***
**Q-8) What are the peak and low season months for EV sales based on the data from 2022 to 2024?**

![Screenshot 2024-07-26 195441](https://github.com/user-attachments/assets/e0cabd92-8e22-4261-90e1-5e0ebdf24c81)
![Screenshot 2024-07-26 195451](https://github.com/user-attachments/assets/9f313ebc-67c8-4576-9fde-c6a7c0f5703e)

similary , we can find the max,min for the fy year 2023 and 2024

![Screenshot 2024-07-26 195506](https://github.com/user-attachments/assets/573beb74-fe70-4826-b1d2-4da32794ccb7)
![Screenshot 2024-07-26 195531](https://github.com/user-attachments/assets/d6601da5-bc65-4486-8089-549c898cab28)
![Screenshot 2024-07-26 195554](https://github.com/user-attachments/assets/e65a5c89-32ce-48ea-83e0-11578d0c4418)



