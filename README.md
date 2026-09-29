# Spice Plate

Restaurant storefront and food-ordering demo, built with HTML, CSS, and JavaScript. The homepage features Spice Plate dishes; customers can create an account, browse the full menu, add items to a cart, and place an order.

## How to open

Install the browser hash dependency, then start the local server:

```
npm install
npx --yes serve .
```

Open the local URL shown on your PC. To use a phone, open the **Network** URL shown by the server on the same Wi-Fi network. Keep the server running on your PC.

## Ordering demo

1. Register a customer or register `darshan00d007@gmail.com` as the owner.
2. Add food to your cart, edit quantities, and place an order.
3. Pay with GPay, Paytm, FamPay, or cash on delivery.
4. Owner login (`darshan00d007@gmail.com`) shows **Edit products**.

## Order email

Each order emails **darshan00d007@gmail.com** (food names, quantities, total, time) via FormSubmit, and also opens the mail app as a backup. The first FormSubmit message needs a one-time confirm link in Gmail.
