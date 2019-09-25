`In order to use public transport
As a customer
I want money on my card`

Objects | Messages
Card    | Money / Balance

`In order to keep using public transport
As a customer
I want to add money to my card`

`C5 - How can you access instance variable outside the instance they belong to? --> FIND OUT`

Objects | Messages
        | Top_up amount to card

`In order to protect my money from theft or loss
As a customer
I want a maximum limit (of £90) on my card`

`How can you check an expression raises an error with RSpec? Why do you have to pass the code as a block to do this? --> FIND OUT`

Objects | Messages
        | Max balance set to £90

`In order to pay for my journey
As a customer
I need my fare deducted from my card`

Objects | Messages
`In order to pay for my journey
As a customer
When my journey is complete, I need the correct amount deducted from my card`


Objects | Messages
        | Deduct amount from card
`In order to get through the barriers.
As a customer
I need to touch in and out.`

Objects | Messages
card    | touch_in, touch_out, in_journey?

`In order to pay for my journey
As a customer
I need to have the minimum amount (£1) for a single journey.`

Objects | Messages

`In order to pay for my journey
As a customer
I need to know where I've travelled from`

Objects | Messages
customer |
card    | record_entry_station
entry_station

card ---> record_entry_station <--- entry_station

`In order to know where I have been
As a customer
I want to see all my previous trips`

Objects | Messages
customer |
card    | 
journey_history | journey_history

card ---> record_journey_history <--- journey_station
