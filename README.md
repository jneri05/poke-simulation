# Pokémon Pack Simulation

## Introduction
A simple simulation that shows probability of getting your money's worth and estimating expected value after 10,000 trials. Factors like a card being worth a lot more then other cards belonging to the set are considered outliers and not included in order to keep the simulation simple. We use a weighted vector representing possible cards you could get from a pack and assigned them an average value for each rarity. After 10,000 trials a table is outputted showing how many times you got each rarity. We then take the proportion of the table to get the probability of each rarity and also see that it matches the intended weighted vector probabilities. Lastly the total cost and net profit are calculated from the 10,000 trials only using profitable rarities since lower tier rarities are harder to sell and usually only sold in bulk. A visualization graph is provided showing the cumulative net profit.

## Outputs

<img width="89" height="31" alt="image" src="https://github.com/user-attachments/assets/9c94562f-fa3a-41f7-bf8c-5a7c108a3ef6" />

Table shows how many times a pack ended with some rarity. 1 = lowest 4 = highest

<img width="137" height="35" alt="image" src="https://github.com/user-attachments/assets/27ee624e-fe44-4c3f-aeb6-effc2223f638" />

Proportions for each rarity match the proposed probabilities of the weighted vector. 1 = 70%, 2 = 13.3%, 3 = 13.3%, 4 = 3.3%

<img width="700" height="432" alt="image" src="https://github.com/user-attachments/assets/94f2b769-05b6-40a8-b0aa-bf324d177a27" />

Summary of the total cost, return from profitable packs, and net profit over 10,000 packs.

## Limitations
- Simple model doesn't represent all possible rarities and large cost
- Rarities in real life are grouped together if they similar odds in the weighted vector.

## Requirements
- R
- R.Studio
