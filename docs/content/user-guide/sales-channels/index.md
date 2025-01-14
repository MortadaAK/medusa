# Sales Channels Overview

In this document, you’ll get an overview of sales channels in Medusa and learn about their importance in your ecommerce store.

:::note

Sales Channels are currently in beta mode and need to be [manually enabled in your store using feature flags](https://medusajs.com/blog/medusa-1-3-5-introducing-sales-channel-api#how-to-enable-sales-channels). If you’re unsure how that works, please contact your technical team.

:::

## Overview

Sales Channels are multiple channels that you can sell your products through. For example, you can have a sales channel for the web storefront, another for the mobile app, and another for selling across social media platforms.

By default, there’s a default sales channel in a Medusa store. You can add multiple sales channels.

## How Sales Channels Work

Sales channels are associated with data and settings in your ecommerce store.

For each sales channel, you can choose which products belong to that sales channel. A product can be available in more than one sales channel.

Then, when customers place an order from a sales channel, the order is associated with that sales channel. You’ll be able to see the sales channel an order was placed from in the Medusa admin.

## Sales Channels Settings Overview

To view the available sales channels and settings, go to Settings → Sales channels.

In the sales channels settings page, You can view available sales channels, add more sales channels, edit sales channels, and manage products available in the sales channel.

![Overview of Sales Channels Page](https://i.imgur.com/9433HAR.png)

## View Sales Channels of Orders

### Orders Page

In the Orders page, you can see the sales channel an order belongs to. If the order doesn’t belong to any sales channel, you can see “N/A” instead.

![Sales Channel column in Orders page](https://i.imgur.com/0tmYOn0.png)

### Orders Details Page

In the details page of an order, you can find the sales channel the order belongs to, if there are any.

![Sales Channel name in the Orders Details page](https://i.imgur.com/hqyYy0E.png)

## View Sales Channels of Products

### Products Page

In the Products page, you can see the sales channels a product belongs to under the Availability column if there are any.

![Sales Channel of a product can be shown under the Availability column on the Products page](https://i.imgur.com/SjaM1aq.png)

### Products Edit Page

In the edit page of a product, you can find the sales channels the product belongs to and edit them under the Sales Channels section.

![Sales Channels a product belongs to can be seen on the Edit Product page](https://i.imgur.com/m9n9viV.png)

## What More Can you Do with Sales Channels?

In the Medusa admin, you can manage the details of sales channels, their products, and more. You can learn more in [this guide](./manage.mdx).
