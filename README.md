# LimoGang Staging Auto Tests

//E-SHOP Entry 
Feature('E-SHOP Entry Button');

Scenario('test something', (I) => {
I.amOnPage('/')
I.click('#enter-div');
I.retry({ retries: 2, minTimeout: 1000 }).see('ZNAČKY')
 });

//E-SHOP Member's Entry    
Feature('E-SHOP Entry Button');

Scenario('test something', (I) => {
I.amOnPage('/')
I.click('#login-div');
I.fillField('#email', 'pavel@big.com');
I.fillField('#password', 'Heslo01');
I.click('#login-btn');
I.retry({ retries: 2, minTimeout: 1000 }).see('ZNAČKY')
 });

//Top Navigation Bar "ZNAČKY" 
Feature('Top Navigation Bar Buttons');

Scenario('test something', (I) => {
I.amOnPage('/')
I.click('#enter-div'); 
I.click('#menu li:nth-child(3)');
I.see('Zachutná na třetí lok.')
 });

//Top Navigation Bar "E-SHOP" 
Feature('Top Navigation Bar Buttons');

Scenario('test something', (I) => {
I.amOnPage('/')
I.click('#enter-div'); 
I.click('#menu li:nth-child(3)');
I.click('#menu li:nth-child(2)');
I.see('BIO!')
 });

//Top Navigation Bar "KONTAKT" 
Feature('Top Navigation Bar Buttons');

Scenario('test something', (I) => {
I.amOnPage('/')
I.click('#enter-div'); 
I.click('#menu li:nth-child(4)');
I.see('Richard Choleva')
 });

//Top Navigation Bar "LIMOGANG LOGO" 
Feature('Top Navigation Bar Buttons');

Scenario('test something', (I) => {
I.amOnPage('/')
I.click('#enter-div'); 
I.click('#header-image');
I.see('Vstoupit')
 });

//Top Navigation Bar "INSTAGRAM" 
Feature('Top Navigation Bar Buttons');

Scenario('test something', (I) => {
I.amOnPage('/')
I.click('#enter-div'); 
I.click('#menu li:nth-child(5)');
I.retry({ retries: 2, minTimeout: 1000 }).see('By signing up, you agree to our Terms.')
 });

//Add Items to the Basket 
Feature('First Item');

Scenario('test something', (I) => {
I.amOnPage('/')
I.click('#enter-div');
I.wait(2)
I.click('.product:nth-of-type(1)');
I.see('Zboží bylo přidáno do košíku')
});

//Add Items to the Basket 
Feature('Second Item');

Scenario('test something', (I) => {
I.amOnPage('/')
I.click('#enter-div');
I.wait(2)
I.click('.product:nth-of-type(2)');
I.see('Zboží bylo přidáno do košíku')
});

//Add Items to the Basket 
Feature('Third Item');

Scenario('test something', (I) => {
I.amOnPage('/')
I.click('#enter-div');
I.wait(2)
I.click('.product:nth-of-type(3)');
I.see('Zboží bylo přidáno do košíku')
});

//Add Items to the Basket 
Feature('Fourth Item');

Scenario('test something', (I) => {
I.amOnPage('/')
I.click('#enter-div');
I.wait(2)
I.click('.product:nth-of-type(4)');
I.see('Zboží bylo přidáno do košíku')
});

//Add Items to the Basket 
Feature('Fifth Item');

Scenario('test something', (I) => {
I.amOnPage('/')
I.click('#enter-div');
I.wait(2)
I.click('.product:nth-of-type(5)');
I.see('Zboží bylo přidáno do košíku')
});

//Add Items to the Basket 
Feature('Sixth Item');

Scenario('test something', (I) => {
I.amOnPage('/')
I.click('#enter-div');
I.wait(2)
I.click('.product:nth-of-type(6)');
I.see('Zboží bylo přidáno do košíku')
});

//Add Items to the Basket 
Feature('Seventh Item');

Scenario('test something', (I) => {
I.amOnPage('/')
I.click('#enter-div');
I.wait(2)
I.click('.product:nth-of-type(7)');
I.see('Zboží bylo přidáno do košíku')
});

//Add Items to the Basket 
Feature('Eighth Item');

Scenario('test something', (I) => {
I.amOnPage('/')
I.click('#enter-div');
I.wait(2)
I.click('.product:nth-of-type(8)');
I.see('Zboží bylo přidáno do košíku')
});

//Add Items to the Basket 
Feature('Ninth Item');

Scenario('test something', (I) => {
I.amOnPage('/')
I.click('#enter-div');
I.wait(2)
I.click('.product:nth-of-type(9)');
I.see('Zboží bylo přidáno do košíku')
});

//Add Items to the Basket 
Feature('Tenth Item');

Scenario('test something', (I) => {
I.amOnPage('/')
I.click('#enter-div');
I.wait(2)
I.click('.product:nth-of-type(10)');
I.see('Zboží bylo přidáno do košíku')
});

//Add Items to the Basket 
Feature('Eleventh Item');

Scenario('test something', (I) => {
I.amOnPage('/')
I.click('#enter-div');
I.wait(2)
I.click('.product:nth-of-type(11)');
I.see('Zboží bylo přidáno do košíku')
});

//Add Items to the Basket 
Feature('Twelfth Item');

Scenario('test something', (I) => {
I.amOnPage('/')
I.click('#enter-div');
I.wait(2)
I.click('.product:nth-of-type(12)');
I.see('Zboží bylo přidáno do košíku')
});

//Add Items to the Basket 
Feature('Thirteenth Item');

Scenario('test something', (I) => {
I.amOnPage('/')
I.click('#enter-div');
I.wait(2)
I.click('.product:nth-of-type(13)');
I.see('Zboží bylo přidáno do košíku')
});

