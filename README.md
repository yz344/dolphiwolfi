

# Personal Website of DolphiWolfi—dolphiwolfi.com

## 1. Introduction

The website dolphiwolfi.com is named after the pen name of Yuchang Zhou, who is a graphic designer and illustrator active on the internet. This website will serve as a personal website of dolphiwolfi, which will include dolphiwolfi's basic information and works. In conclusion, it will work as both a resume and a portfolio. Additionally, it will provide information about her works on sale.

Below is the general sections of dolphiwolfi.com:
1. Index
2. Biography
3. Design
4. Illustration
5. Articles
6. Projects
7. Presents and specials
8. Goods on sale
9. Links
10. Contact

## 2. Component Design Documentation

### 2.1 Index

1. Navigation bar
2. A impressive background picture
3. 



## 3. Sketches

[2. Create some sketches to generate ideas about a website design that would work for your persona.]

Firstly, after reading Abby's portfolio, I noticed that it consists of four parts, namely a brief introduction, background and skills, motivations and attitudes, and how Abby works with information and learns, therefore I decide to make intogether four webpages, and one for each part, which is very clear.

Secondly, for each part I put navigation bar on the left in order to provide visitor a clear overview. And the heading of the current webpage will show on the top of the page, followed by the content. And I give sub-headings to paragraphs in the content.

Sketch 1: Home

![](sketch1_home.jpg)

Sketch 2: Background and skills

![](sketch2_bkgd.jpg)

Sketch 3: Motivations and Attitudes

![](sketch3_moti.jpg)

Sketch 4: How Abby Works with Information and Learns

![](sketch4_work.jpg)

Added after milestone:

Sketch 5: Contact

![](sketch5_contact.jpg)

## 3. Wireframes

[3. Author detailed wireframes that will become the design that you program for the final milestone.]

I did two major changes to wireframe after submission of milestone1.
The first is to change the vertical navigation bar to horizontal, because I find it more clear to have a horizontal bar on the top. And I move the vertical navigation bar to the footer, so that user can easily find navigation when they are viewing the bottom of pages.

The second is to add a page, which is the contact page.

Despite of these two changes, the websites follow the original wireframes.

Wireframe 1: Home

![](wireframe1_home.jpg)

New Wireframe 1

![](wireframe_home_new.jpg)

Wireframe 2: Background and skills

![](wireframe2_bkgd.jpg)

New Wireframe 2

![](wireframe_bkgd_new.jpg)

Wireframe 3: Motivations and Attitudes

![](wireframe3_moti.jpg)

New Wireframe 3

![](wireframe_moti_new.jpg)

Wireframe 4: How Abby Works with Information and Learns

![](wireframe4_work.jpg)

New Wireframe 4

![](wireframe_work_new.jpg)

Wireframe 5: Contact

![](wireframe_contact.jpg)

Major changes:

![](wireframe_change_new.jpg)

## 4. Coding Plan & Pseudocode

[4. Author a plan for how you will code your PHP website.]

My PHP websites consist of home.php, bkgd.php, moti.php and work.php. All the above phps include header.php, footer.php and init.php, which are all in *includes* directory. The init.php will include an associative array which works as the navigation, and it will direct to all the four pages using current id. The header.php will have title and navigation bar, which loops through the associative array in init.php. And the footer.php may include contact information, footnotes and credit to resources.

[Write your pseudocode for your user defined function.]


**header.php**

      function mark_current_page() begin
      foreach($pages as $page => $name){
        if($current_page_id == $page){
        echo "you are on the xxx page!"}
      }

**bkgd, moti and work.php**

      $contents = {each line of the contents}
      function show_contents() begin
      echo htmlspecialchars($contents[0]);
      echo htmlspecialchars($contents[1]); etc.
      end

## 5. Reference&Credits

I refer to the function in labs, just as reference. And I commented the reference in the code.

Contents adapted from Abby's persona are given credit.

All images used belong to myself.
