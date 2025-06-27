# Issues Fixed 

## Data null issue 
the src/app/components/CommunityInfo.js had issue where the state variable and the variable used to store fetched data had the same name 'data'
i fixed that in the following way
![image](https://github.com/user-attachments/assets/41e5d8d1-4609-4880-8289-b16cdfb51bd7)
Note:the console.log('data') and console.log(data) were written for debugging purpose and can be safely removed 

## Diffrent date on which hackweek ends
the src/app/components/Countdown.js had the end date as 29th of june but actually the hackweek ends on 28th of june, the below changes were made by me
![image](https://github.com/user-attachments/assets/948b0924-54ce-4135-b4d3-33b04f73975d)


## Minor dev issue solved
Hydration errors occur when there's a mismatch between the HTML generated on the server and what React expects to render on the client during the reconciliation process
i used suppressHydrationWarning,check the image given below
![image](https://github.com/user-attachments/assets/450b037b-d3aa-4eff-9293-b3eada260269)


# Site after solving issues
![image](https://github.com/user-attachments/assets/88cab238-866c-44a5-b0b0-36bbe1ccfe79)
