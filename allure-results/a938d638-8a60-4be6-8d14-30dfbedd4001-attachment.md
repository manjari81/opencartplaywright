# Test info

- Name: Login Test with JSON Data: Invalid login @datadriven
- Location: C:\opencartplaywright\tests\LoginDataDriven.spec.ts:17:8

# Error details

```
Error: expect(received).toBe(expected) // Object.is equality

Expected: " Warning: No match for E-Mail Address and/or Password."
Received: " Warning: Your account has exceeded allowed number of login attempts. Please try again in 1 hour."
    at C:\opencartplaywright\tests\LoginDataDriven.spec.ts:38:34
```

# Page snapshot

```yaml
- navigation:
  - button "$ Currency ":
    - strong: $
    - text: Currency 
  - list:
    - listitem:
      - link "":
        - /url: http://localhost/opencart/upload/index.php?route=information/contact
      - text: "123456789"
    - listitem:
      - link " My Account":
        - /url: http://localhost/opencart/upload/index.php?route=account/account
    - listitem:
      - link " Wish List (0)":
        - /url: http://localhost/opencart/upload/index.php?route=account/wishlist
    - listitem:
      - link " Shopping Cart":
        - /url: http://localhost/opencart/upload/index.php?route=checkout/cart
    - listitem:
      - link " Checkout":
        - /url: http://localhost/opencart/upload/index.php?route=checkout/checkout
- banner:
  - link "Your Store":
    - /url: http://localhost/opencart/upload/index.php?route=common/home
    - img "Your Store"
  - textbox "Search"
  - button ""
  - button " 0 item(s) - $0.00"
- navigation:
  - list:
    - listitem:
      - link "Desktops":
        - /url: http://localhost/opencart/upload/index.php?route=product/category&path=20
    - listitem:
      - link "Laptops & Notebooks":
        - /url: http://localhost/opencart/upload/index.php?route=product/category&path=18
    - listitem:
      - link "Components":
        - /url: http://localhost/opencart/upload/index.php?route=product/category&path=25
    - listitem:
      - link "Tablets":
        - /url: http://localhost/opencart/upload/index.php?route=product/category&path=57
    - listitem:
      - link "Software":
        - /url: http://localhost/opencart/upload/index.php?route=product/category&path=17
    - listitem:
      - link "Phones & PDAs":
        - /url: http://localhost/opencart/upload/index.php?route=product/category&path=24
    - listitem:
      - link "Cameras":
        - /url: http://localhost/opencart/upload/index.php?route=product/category&path=33
    - listitem:
      - link "MP3 Players":
        - /url: http://localhost/opencart/upload/index.php?route=product/category&path=34
- list:
  - listitem:
    - link "":
      - /url: http://localhost/opencart/upload/index.php?route=common/home
  - listitem:
    - link "Account":
      - /url: http://localhost/opencart/upload/index.php?route=account/account
  - listitem:
    - link "Login":
      - /url: http://localhost/opencart/upload/index.php?route=account/login
- text: " Warning: Your account has exceeded allowed number of login attempts. Please try again in 1 hour."
- heading "New Customer" [level=2]
- paragraph:
  - strong: Register Account
- paragraph: By creating an account you will be able to shop faster, be up to date on an order's status, and keep track of the orders you have previously made.
- link "Continue":
  - /url: http://localhost/opencart/upload/index.php?route=account/register
- heading "Returning Customer" [level=2]
- paragraph:
  - strong: I am a returning customer
- text: E-Mail Address
- textbox "E-Mail Address": abcxyz@xyz.com
- text: Password
- textbox "Password": abcxyx
- link "Forgotten Password":
  - /url: http://localhost/opencart/upload/index.php?route=account/forgotten
- button "Login"
- complementary:
  - link "Login":
    - /url: http://localhost/opencart/upload/index.php?route=account/login
  - link "Register":
    - /url: http://localhost/opencart/upload/index.php?route=account/register
  - link "Forgotten Password":
    - /url: http://localhost/opencart/upload/index.php?route=account/forgotten
  - link "My Account":
    - /url: http://localhost/opencart/upload/index.php?route=account/account
  - link "Address Book":
    - /url: http://localhost/opencart/upload/index.php?route=account/address
  - link "Wish List":
    - /url: http://localhost/opencart/upload/index.php?route=account/wishlist
  - link "Order History":
    - /url: http://localhost/opencart/upload/index.php?route=account/order
  - link "Downloads":
    - /url: http://localhost/opencart/upload/index.php?route=account/download
  - link "Recurring payments":
    - /url: http://localhost/opencart/upload/index.php?route=account/recurring
  - link "Reward Points":
    - /url: http://localhost/opencart/upload/index.php?route=account/reward
  - link "Returns":
    - /url: http://localhost/opencart/upload/index.php?route=account/return
  - link "Transactions":
    - /url: http://localhost/opencart/upload/index.php?route=account/transaction
  - link "Newsletter":
    - /url: http://localhost/opencart/upload/index.php?route=account/newsletter
- contentinfo:
  - heading "Information" [level=5]
  - list:
    - listitem:
      - link "About Us":
        - /url: http://localhost/opencart/upload/index.php?route=information/information&information_id=4
    - listitem:
      - link "Delivery Information":
        - /url: http://localhost/opencart/upload/index.php?route=information/information&information_id=6
    - listitem:
      - link "Privacy Policy":
        - /url: http://localhost/opencart/upload/index.php?route=information/information&information_id=3
    - listitem:
      - link "Terms & Conditions":
        - /url: http://localhost/opencart/upload/index.php?route=information/information&information_id=5
  - heading "Customer Service" [level=5]
  - list:
    - listitem:
      - link "Contact Us":
        - /url: http://localhost/opencart/upload/index.php?route=information/contact
    - listitem:
      - link "Returns":
        - /url: http://localhost/opencart/upload/index.php?route=account/return/add
    - listitem:
      - link "Site Map":
        - /url: http://localhost/opencart/upload/index.php?route=information/sitemap
  - heading "Extras" [level=5]
  - list:
    - listitem:
      - link "Brands":
        - /url: http://localhost/opencart/upload/index.php?route=product/manufacturer
    - listitem:
      - link "Gift Certificates":
        - /url: http://localhost/opencart/upload/index.php?route=account/voucher
    - listitem:
      - link "Affiliate":
        - /url: http://localhost/opencart/upload/index.php?route=affiliate/login
    - listitem:
      - link "Specials":
        - /url: http://localhost/opencart/upload/index.php?route=product/special
  - heading "My Account" [level=5]
  - list:
    - listitem:
      - link "My Account":
        - /url: http://localhost/opencart/upload/index.php?route=account/account
    - listitem:
      - link "Order History":
        - /url: http://localhost/opencart/upload/index.php?route=account/order
    - listitem:
      - link "Wish List":
        - /url: http://localhost/opencart/upload/index.php?route=account/wishlist
    - listitem:
      - link "Newsletter":
        - /url: http://localhost/opencart/upload/index.php?route=account/newsletter
  - separator
  - paragraph:
    - text: Powered By
    - link "OpenCart":
      - /url: http://www.opencart.com
    - text: Your Store © 2025
```

# Test source

```ts
   1 | import { test, expect } from '@playwright/test';
   2 | import { LoginPage } from '../pages/LoginPage';
   3 | import { MyAccountPage } from '../pages/MyAccountPage';
   4 | import { DataProvider } from '../utils/dataProvider';
   5 | import { TestConfig } from '../test.config';
   6 | import { HomePage } from '../pages/HomePage';
   7 |
   8 |
   9 | //Load JSON test data logindata.json
  10 |
  11 | const jsonPath="testdata/logindata.json";
  12 | const jsonTestData=DataProvider.getTestDataFromJson(jsonPath);
  13 |
  14 |
  15 | for(const data of jsonTestData)
  16 | {
  17 |    test(`Login Test with JSON Data: ${data.testName} @datadriven`, async({page})=>{
  18 |
  19 |         const config = new TestConfig(); // create instance
  20 |         await page.goto(config.appUrl);    // getting appURL from test.config.ts file
  21 |
  22 |         const homePage = new HomePage(page);
  23 |         await homePage.clickMyAccount();
  24 |         await homePage.clickLogin();
  25 |
  26 |         const loginPage = new LoginPage(page);
  27 |         await loginPage.login(data.email, data.password);
  28 |
  29 |         if(data.expected.toLowerCase()==='success')
  30 |         {
  31 |             const myAccountPage=new MyAccountPage(page);
  32 |             const isLoggedIn=await myAccountPage.isMyAccountPageExists();
  33 |             expect(isLoggedIn).toBeTruthy();
  34 |
  35 |         }
  36 |         else{
  37 |             const errorMessage=await loginPage.getloginErrorMessage();
> 38 |             expect(errorMessage).toBe(' Warning: No match for E-Mail Address and/or Password.');
     |                                  ^ Error: expect(received).toBe(expected) // Object.is equality
  39 |            // expect(errorMessage).toContain('Warning: No match');
  40 |           // expect(errorMessage).toContain(' Warning: Your account has exceeded allowed number of login attempts. Please try again in 1 hour.');  
  41 |         }
  42 |     })
  43 |
  44 | }
  45 |
  46 |
  47 |
  48 | //Load CSV test data logindata.json
  49 |
  50 | const csvPath = "testdata/logindata.csv";
  51 | const csvTestData = DataProvider.getTestDataFromCsv(csvPath);
  52 |
  53 |
  54 | for(const data of csvTestData)
  55 | {
  56 |    test (`Login Test with CSV Data: ${data.testName} @datadriven`, async({page})=>{
  57 |
  58 |         const config = new TestConfig(); // create instance
  59 |         await page.goto(config.appUrl);    // getting appURL from test.config.ts file
  60 |
  61 |         const homePage = new HomePage(page);
  62 |         await homePage.clickMyAccount();
  63 |         await homePage.clickLogin();
  64 |
  65 |         const loginPage = new LoginPage(page);
  66 |         await loginPage.login(data.email, data.password);
  67 |
  68 |         if(data.expected.toLowerCase()==='success')
  69 |         {
  70 |             const myAccountPage=new MyAccountPage(page);
  71 |             const isLoggedIn=await myAccountPage.isMyAccountPageExists();
  72 |             expect(isLoggedIn).toBeTruthy();
  73 |
  74 |         }
  75 |         else{
  76 |             const errorMessage=await loginPage.getloginErrorMessage();
  77 |             //expect(errorMessage).toBe('Warning: No match for E-Mail Address and/or Password.');
  78 |             // expect(errorMessage).toContain('Warning: No match'); 
  79 |            expect(errorMessage).toContain(' Warning: Your account has exceeded allowed number of login attempts. Please try again in 1 hour.');   
  80 |         }
  81 |     })
  82 |
  83 | }
```