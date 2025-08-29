# Royal Rosarian Foundation - Website Script & Navigation Structure

*UX Design Specification | November 2024*

## Header Section
```html
<HEADER; ROLE=BANNER>
  <H1 PAGE TITLE>
    "Welcome to the Royal Rosarian Foundation – Supporting Community Growth and Service"
  </H1>
  <!-- PURPOSE: One statement explanation of the purpose of the Foundation website -->
  
  <LOGO; Alt="Click here to return to homepage">
  <SEARCH; Alt="Search Bar">
```

## Navigation Menu
```html
<NAV; ROLE=NAVIGATION>
  <FAT MENU>
    <SECTION; ROLE=REGION>
      <TITLE><H3 SUBHEADER>Impact</H3>
      <MENU ITEM><H4>
      <MENU ITEM><H4>
      <MENU ITEM><H4>
    </SECTION>
    
    <SECTION; ROLE=REGION>
      <TITLE><H3 SUBHEADER>Legacy</H3>
      <MENU ITEM><H4>
      <MENU ITEM><H4>
      <MENU ITEM><H4>
    </SECTION>
    
    <SECTION; ROLE=REGION>
      <TITLE><H3 SUBHEADER>Partner</H3>
      <MENU ITEM><H4>
      <MENU ITEM><H4>
      <MENU ITEM><H4>
    </SECTION>
    
    <SECTION; ROLE=REGION>
      <TITLE><H3 SUBHEADER>Royal Rosarian Site</H3>
      <MENU ITEM><H4>[Portal; External link to the organization website]
    </SECTION>
    
    <SECTION; ROLE=REGION>
      <TITLE><H3 SUBHEADER>Support</H3>
      <MENU ITEM><H4>[Donation Button; External link to Stripe?]
    </SECTION>
  </FAT MENU>
</NAV>
```

## Homepage Content Structure

### Hero Section
```html
<MAIN; ROLE=MAIN>
  <H2 MAIN HEADING>
  <SECTION; ROLE=REGION>
    <H3 SUBHEADER>
    <ARTICLE; ROLE=ARTICLE>
      <H4 SUBHEADER>"Support Community Programs"</H4>
      <!-- PURPOSE: Broad label title for this section -->
      
      <TITLE>
        <H5 SUBHEADER>"For You, a Rose in Portland Grows"</H5>
        <!-- PURPOSE: Giant hero image -->
      </TITLE>
      
      [Hero Image; Alt: "Image of happy elementary school children holding roses up to the camera"]
      "Learn about our mission and impact."
      [Donate Now; Link to Stripe] [Learn More; Link to about page]
    </ARTICLE>
  </SECTION>
</MAIN>
```

### Cultivating Portland's Future Section
```html
<SECTION; ROLE=REGION>
  <H3 SUBHEADER>
  <ARTICLE; ROLE=ARTICLE>
    <H4 SUBHEADER>Cultivating Portland's Future</H4>
    <!-- PURPOSE: high level metrics, vanity stats that appeal to potential donors -->
    
    <TITLE><H5 SUBHEADER>
    <P>Example: Transitional School
    <figure>XXX Helped</figure>
    
    <TITLE><H5 SUBHEADER>
    <P>Example: Field Trips
    <figure>XXX Helped</figure>
    
    <TITLE><H5 SUBHEADER>
    <P>Example: Community Enrichment
    <figure>XXX Helped</figure>
  </ARTICLE>
</SECTION>
```

### Mission Statement Section
```html
<SECTION; ROLE=REGION>
  <H3 SUBHEADER>Mission Statement</H3>
  <ARTICLE; ROLE=ARTICLE>
    <H4 SUBHEADER>
    To provide financial support for programs and projects that improve the livability of the greater Portland community and promote or enable participation in the Portland Rose Festival. Fund programs to foster the education of young individuals through our Field Trip program and music scholarships. Also serve the community through various historical activities that honor the Portland Rose Festival Foundation and the Royal Rosarians.
    
    "Dedicated to enriching the community through charitable support, education, and the celebration of tradition."
    [A: Learn More]
  </ARTICLE>
</SECTION>
```

### Make an Impact Section
```html
<NAV; ROLE=NAVIGATION>
  <FAT MENU>Make an Impact…</FAT MENU>
  <!-- Purpose: highlight all the causes the RRF serves to establish credibility -->
  
  <SECTION; ROLE=REGION>
    <TITLE><H3 SUBHEADER>Children</H3>
    <MENU ITEM><H4>Transitional School</H4>
    <MENU ITEM><H4>Field Trips</H4>
    <MENU ITEM><H4>Christmas for kids</H4>
  </SECTION>
  
  <SECTION; ROLE=REGION>
    <TITLE><H3 SUBHEADER>Community</H3>
    <MENU ITEM><H4>Rose Garden Contest</H4>
    <MENU ITEM><H4>Queens' Garden Party</H4>
    <MENU ITEM><H4>Royal Rosarian Floats</H4>
    <MENU ITEM><H4>Milk Carton Boat Race</H4>
  </SECTION>
  
  <SECTION; ROLE=REGION>
    <TITLE><H3 SUBHEADER>Members</H3>
    <MENU ITEM><H4>Clothing Closet</H4>
    <MENU ITEM><H4></H4>
  </SECTION>
</NAV>
```

### Stories Section
```html
<SECTION; ROLE=REGION>
  <H3 SUBHEADER>Stories</H3>
  <!-- PURPOSE: Call out success stories from community and/or members -->
  
  <ARTICLE; ROLE=ARTICLE>
    <H4 SUBHEADER>Testimonials… See Thank you notes tab</H4>
    
    <TITLE>Field Trip Program</TITLE>
    <H5 SUBHEADER>
    <P>Lorem
    <a>Learn More…</a>
    
    <TITLE><H5 SUBHEADER>
    <P>Lorem
    <a>Learn More…</a>
    
    <TITLE><H5 SUBHEADER>
    <P>Lorem
    <a>Learn More…</a>
  </ARTICLE>
</SECTION>
```

### Impact Report Section
```html
<SECTION; ROLE=REGION>
  <H3 SUBHEADER>Impact Report</H3>
  <!-- Purpose: More metrics/ numbers / stats to demonstrate organization's transparency -->
  
  <ARTICLE; ROLE=ARTICLE>
    <H4 SUBHEADER>
    "Securing Your Support for Community Programs."
    [A: Learn More]
  </ARTICLE>
</SECTION>
```

### Join Us Section
```html
<SECTION; ROLE=REGION>
  <H3 SUBHEADER>Join Us</H3>
  <!-- PURPOSE: Encourage site visitors to learn more about membership benefits or ways to support -->
  
  <ARTICLE; ROLE=ARTICLE>
    <H4 SUBHEADER>Ways to get involved</H4>
    
    <TITLE><H5 SUBHEADER>
    <P>Donate
    <a>Learn More…</a>
    
    <TITLE><H5 SUBHEADER>
    <P>Membership
    <a>Learn More…</a>
    
    <TITLE><H5 SUBHEADER>
    <P>Auction
    <a>Learn More…</a>
  </ARTICLE>
</SECTION>
```

## Footer Section
```html
<FOOTER; ROLE=CONTENTINFO>
  Informational child content such as footnotes, copyrights, links to privacy statements, links preferences, etc
  
  <NAV; ROLE=NAVIGATION>
    <FAT MENU>
    The area that contains the navigation links for the document or web site.
    
    <SECTION; ROLE=REGION>
      <TITLE><H3 SUBHEADER>
      <MENU ITEM><H4>
      <MENU ITEM><H4>
      <MENU ITEM><H4>
    </SECTION>
    
    <SECTION; ROLE=REGION>
      <TITLE><H3 SUBHEADER>
      <MENU ITEM><H4>
      <MENU ITEM><H4>
      <MENU ITEM><H4>
    </SECTION>
    
    <SECTION; ROLE=REGION>
      <TITLE><H3 SUBHEADER>
      <MENU ITEM><H4>
      <MENU ITEM><H4>
      <MENU ITEM><H4>
    </SECTION>
  </NAV>
</FOOTER>
```

---

*Document created November 2024 | Royal Rosarian Foundation – UX Design by Meghan Jimenez*