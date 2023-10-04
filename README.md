# Khalti php integration

This is an initiate for easier implementation of khalti payment gateway for beginners in php.

Please contribute for further more features.

## How to use it ?

1. Copy the file pay.php and khalti.png to your project folder
2. change `$khalti_public_key` with your api public key.
3. write code to get your product id, name , url and price
4. change `$successRedirect` variable. When payment will be success, this url will be called.
5. run your code to verify transaction after successful transaction, this can be used to update database or do more action on success. use `checkValid()` function for this.
6. Don't forget to give a star to this repo.
7. For contribution, please contact me https://samirk.com.np

## License

- It is free to use and mofify for any purpose. I don't take responsibility for misusage, you will be responsible for your action.

## Version

Currently, this system use khalti v2 api endpoints.

## Resources

- Endpoint Request/Response Docs: https://docs.khalti.com/checkout/diy-wallet/
- Khalti merchant login: https://admin.khalti.com
- Video Tutorial : https://youtu.be/HdhIk4qdnKU?si=-AQpPasvkZYjx2lF
