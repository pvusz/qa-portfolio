qa-portfolio    

/test-cases

/bug-reports

/checklists

/exploratory-sessions

/test-plans

/screenshots/ screencasts

# Test Case: Add a product to the Bag

**Client:** Confidential

**Test ID:** NDA

**URL:** NDA

**Preconditions:**
-Tester on mobile device (IPhone 13 Mini)

-Browser: Google Chrome

-Non-US locales, only test on US store

-submit report in EN

## Test Steps:
1.Go to: (URL under NDA)

2.Tap on *Hamburger Menu*

3.Tap on category *Women's*

4.Tap on subcategory *Shop all Women's*

5.Tap on any *PDP* tile for example *Name under NDA*

6. Select size
   
7.Tap on *Add to bag* button

## Expected Result
User successfully added product to the bag.

**Screenshot:** Under NDA 



# Bug Report: Sticky size selector overlaps "Name under NDA" section

**Bug Type:** Visual

**Feature:** Product Details Page (PDP)

## Steps:
1. Go to: (URL under NDA)
2. Tap on *Shop Men's* button on "Name under NDA" banner
3. Tap on any *PDP* tile for example "Name under NDA"
4. Scroll down the *PDP* until floating size icon shows up
5. Tap on "Name under NDA" icon in the header

## Actual Result:
The size selector overlaps and covers "Name under NDA" section. 

## Expected Result:
The sticky size selector icon should remain propelry positioned and not cover other content, including "Name under NDA" section, during scrolling and interactions.

## Environment

Device: Apple Iphone 13 mini, iOS 18.6.2

Browser: Google Chrome


## Bug Report": Cashback banner "Kup szczoteczkę Philips i odbierz zwrot" link redirects to wrong page

**Bug Type:** Functional

**Feature:** Navigation

**Severity:** High

## Steps: 
1. Go to: https://www.philips.pl/
2. Click on electric brush icon on slider banner
3. Click on "Dowiedz się więcej" button on the same banner
4. Click on link "https://www.philips.pl/c-w/promocje/cashback-philips-sonicare.html" on next banner you were redirected with caption "Elektryczne szczoteczlo do zębów z technologią soniczną Philips Sonicare"
5. Click on link "www.inwestycjawusmiech.pl" on banner under caption "Kup szczoteczkę Philips i odbierz zwrot"

## Actual Results

After clicking link, user is redirected to the electric shaver cashback page instead of the electric toothbrush cashback page. 

## Expected Results 

Clicking the link should navigate user to the correct product page for the electric toothbrush offer.

## Envinronment

Device: Computer, Windows 10

Browser: Firefox

**Screencast:** [View video](philips.navigation-bug.mp4)
