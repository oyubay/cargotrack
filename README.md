# Application name - Cargo Tracker
## Project Topic 
The purpose of this web application is for people who want to track their cargo. Users can login, add cargo information and be able to modify their information as
well as cargo information. 
## Motivation 
Mongolian community in Chicago usually send cargo to Ulaanbaatar. But senders can't able to track their cargo. I am one of the users who send cargo and don't 
have information about it over time. Most of the time, I need to call the cargo company or send a message through Facebook. Sometimes they respond in 2-3 days. 
Also, If I want to send a cargo, I scroll their Facebook page to get information. If there will be a web application that users can log in, and get an update about
their cargo, it would be a lot easier for both senders and cargo companies. For cargo companies, they don't have to answer the same question many times over the 
phone, and for users, they don't need to wait for their response. 
## Design specifications
I chose a flat design style for my web application due to its minimalism and modernism. Flat design tends to use bright colors and 2 dimensional images. I chose 
this color palette: dark blue, mint cream, white and black. Since those colors are easy on eyes, makes Cargo Tracker more attractable. I wanted to make user 
interface friendly as possible such as easy navigation, responsive, clean and simple. User sees only important information.
## Future work
Users be able to track their cargo location that will be updated by cargo company. To do this, might use real time location or entered my manually. 
Users will choose receiver information based on their phone number if they are registered. Therefore, receiver users are able to see what is coming under 
her name and keep track of it. Admin dashboard is needed. Cargo company manager updates some information such as cargo location, estimated time to be delivered 
and  when shipping container will leave.
## Server-Side Components
Users' information will be stored on the server. 
- First name
- Last name
- Phone number
- Address

Package receiver information
- First name
- Last name
- Phone number
- Address

Package information
- what's inside (detailed item names, price, number of that item)
- price
- weight
