# Test info

- Name: User login test @master @sanity @regression
- Location: C:\opencartplaywright\tests\Login.spec.ts:42:5

# Error details

```
Error: expect(received).toBeTruthy()

Received: false
    at C:\opencartplaywright\tests\Login.spec.ts:59:24
```

# Test source

```ts
   1 | /**
   2 |  * Test Case: Login with Valid Credentials
   3 |  * 
   4 |  * Tags: @master @sanity @regression
   5 |  * 
   6 |  * Steps:
   7 |  * 1) Navigate to the application URL
   8 |  * 2) Navigate to Login page via Home page
   9 |  * 3) Enter valid credentials and log in
  10 |  * 4) Verify successful login by checking 'My Account' page presence
  11 |  */
  12 |
  13 | import { test, expect } from '@playwright/test';
  14 | import { HomePage } from '../pages/HomePage';
  15 | import { LoginPage } from '../pages/LoginPage';
  16 | import { MyAccountPage } from '../pages/MyAccountPage';
  17 | import { TestConfig } from '../test.config';
  18 |
  19 | let config: TestConfig;
  20 | let homePage: HomePage;
  21 | let loginPage: LoginPage;
  22 | let myAccountPage: MyAccountPage;
  23 |
  24 | // This hook runs before each test
  25 | test.beforeEach(async ({ page }) => {
  26 |   config = new TestConfig(); // Load config (URL, credentials)
  27 |   await page.goto(config.appUrl); // Navigate to base URL
  28 |
  29 |   // Initialize page objects
  30 |   homePage = new HomePage(page);
  31 |   loginPage = new LoginPage(page);
  32 |   myAccountPage = new MyAccountPage(page);
  33 | });
  34 |
  35 | // Optional cleanup after each test
  36 | test.afterEach(async ({ page }) => {
  37 |   await page.waitForTimeout(3000);
  38 |   await page.close(); // Close browser tab (good practice in local/dev run)
  39 | });
  40 |
  41 |
  42 | test('User login test @master @sanity @regression',async()=>{
  43 |
  44 |     //Navigate to Login page via Home page
  45 |
  46 |     await homePage.clickMyAccount();
  47 |     await homePage.clickLogin();
  48 |
  49 |     //Enter valid credentials and log in
  50 |     await loginPage.setEmail(config.email);
  51 |     await loginPage.setPassword(config.password);
  52 |     await loginPage.clickLogin();
  53 |
  54 |     //alternatively
  55 |     //await loginPage.login(config.email,config.password);
  56 |
  57 |     //Verify successful login by checking 'My Account' page presence
  58 |     const isLoggedIn=await myAccountPage.isMyAccountPageExists();
> 59 |     expect(isLoggedIn).toBeTruthy();
     |                        ^ Error: expect(received).toBeTruthy()
  60 |     
  61 |
  62 | })
  63 |
  64 |
```