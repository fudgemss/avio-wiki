# Miles Programme

Aside from managing flights, Avio also lets you create a miles programme, which is a perfect way for your server members to earn
exclusive rewards.

## Creating a Miles Programme Shop

1. Run `/miles-create-shop [shopID] [channel]` and fill in the details (the channel is where the shop will be published to)
2. Head to the [dashboard](https://dashboard.aviobot.app) and log in with Discord
3. Navigate to **Miles Programme** in the sidebar
4. Enter your shopID and fill in the rest of the general details
5. Select your rewards, along with how many miles they require (you can have up to 8 rewards)
6. Click **Save Draft**, then **Publish to Discord**

!!! warning "One Shop Limit"
    You can only have one shop per server. If you wish to make a new shop, you will need to
    remove any existing ones.

    You can edit the details of existing shops, explained below.

## Editing an Existing Shop

1. Head to the [dashboard](https://dashboard.aviobot.app) and log in with Discord
2. Navigate to the **Miles Programme** in the sidebar
3. If a shop exists, the details will be preloaded
4. Change the details to your liking
5. Click **Save Draft**, then **Publish to Discord**

This will edit the existing message, rather than publishing a new message.

## Removing a Miles Shop

1. Run `/miles-remove-shop`
2. This will automatically remove your existing shop

This action **cannot be undone**.


## Earning Miles

There are numerous ways you can earn miles, but it depends on your server settings.

### Through Flights
Flight managers can give you miles by participating in flights.

To set this up, use the following:
1. Run `/miles reward [amount]` and enter how many miles you wish to give
2. This will generate a unique code server members can enter

To redeem the miles, server members can do the following:
1. Run `/miles redeem-reward [code]` and enter the code given by the flight manager
2. This will add the miles to your account

Mile codes can only be redeemed once per account.

### Through Chat Games
If your server has it enabled, you can earn miles by getting correct answers in the
chat games. (guess the, aviationwordle).

To enable these settings, do the following:
1. Head to the [dashboard](https://dashboard.aviobot.app) and log in with Discord
2. Navigate to the **Miles Programme** in the sidebar
3. Scroll down to the **Economy Settings**
4. Click the button on **Earn Miles from ChatGames** to enable/disable the feature.

!!! note "View Miles Config"
    You can view the current settings for your miles programme
    by using `/miles-settings`.

## Purchasing Rewards
To purchase rewards from the miles shop, do the following:
1. Run `/miles-purchase [slot]` and enter the slot you would like to purchase
2. If you have enough miles, you will be granted the role and have the miles deducted
3. If you have a unsufficient balance, you will be given an error message 


## Adding/Removing Miles
To remove or add miles to server members, do the following:

1. Run `/miles add [user] [amount]`
2. Run `/miles remove [user] [amount]`

If you wish to fully reset all miles for your server, use the following:
1. Run `/miles wipe`

!!! danger "Action Cannot be Undone"
    This action will wipe ALL miles from ALL users in
    your server. This action CANNOT be undone.


!!! tip "View your Miles"
    You can view your miles using `/miles mymiles`.

    Server admins can use `/miles view [user]` to view the balance
    of any server member.


--- 
