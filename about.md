---
layout: page
title: About
permalink: /about/
---
<div class="about-title">MOMENT
</div>
<div class="about-tagline">Contemporary, courageous, liberal Jekyll theme<br>
for newspapers, magazines and blogs.</div>

<p>
There is some thought out there you wish to pin,
<br>
there is some idea driving crazy, you want something to jot it down,
<br>
there is a story to be told, or a prose to be sung,
<br>
the moment is now.
</p>
<br>
<center><span class="manual">Get up and running with</span> <span class="manual-head">MOMENT</span></center>

<div class="manual-post">
  <div class="manual manual-title">
POSTING
  </div>
<p>  <div class="manual-content">

      - Create a .markdown file inside <code>posts</code> folder.<br />
      - Name the file according to the format YY-MM-DD-[short name for your post].<br />  <code>2016-03-30-i-love-design.markdown</code><br />
      - Write the <a href="jekyll">Front Matter</a> and content in the file.<br />
      <div class="example">
        <span class="manual">FORMAT</span><br />
        <code>---<br />
        layout: post | default | page<br />
        title:  String<span class="hint"> Post Title</span><br />
        date:   Time Stamp<br />
        categories: String | Array of Strings<span class="hint">CASE SENSITIVE! Category / Categories </span><br />
        ---
      </code><br />
      </div>
      <div class="example">

        <code>---<br />
        layout: post<br />
        title:  "The One with the Blackout"<br />
        date:   2016-03-30 19:45:31 +0530<br />
        categories: ["life", "friends"]<br />
        ---
      </code>
      </div>


  </div>
</p>
</div>


<div class="manual-post">
  <div class="manual manual-title">
  CREATE PAGES
  </div>
<p>  <div class="manual-content">

      - Create a .md file in the root directory.<br />
      - Name the file with the desired page link name.<br />  <code>about.md</code><br /><code>design.md</code><br />
      - Write the <a href="jekyll">Front Matter</a> and content in the file.
      <div class="example">
        <span class="manual">FORMAT</span><br />
        <code>---<br />

          layout: page<br />
          title: String <span class="hint">Title of the webpage</span><br />
          permalink: / String / <span class="hint">Permalink for the webpage</span><br />
          tagline: String <span class="hint">Optional Gravity Feature : Tagline for the page</span><br />
          ---
      </code><br />
      </div>
      <div class="example">

        <code>---<br />
        layout: page<br />
        title:  "Science"<br />
        permalink:   /Science/ <br />
        tagline : "Humanity is overrated." <br />
        ---
      </code>
      </div>


  </div>


<br>

  <div class="manual-post">
    <div class="manual manual-title">
  CREATE ARCHIVES/ CATEGORY PAGES
  </div><br />
  <div class="archiveIntro">
    <p>
      Introducing <strong>Archive Pages</strong>.<br /></p>
    <span class="archive-intro">  You can display a list of all the post corresponding to a particular category on a standalone Page using the <code>'archive'</code> layout.
  </span>
  </div>
  <br />

  <p>  <div class="manual-content">

        - Create a .md file in the root directory.<br />
        - Name the file. Preferred name will be the name of the category<br />  <code>life.md</code><br />
        - Change the config.yml file's category attribute and add your new category in the array (CASE SENSITIVE! Be case sensitive everywhere you write category name.)<br />  
        - Write the <a href="jekyll">Front Matter</a> and content in the file.
        <div class="example">
          <span class="manual">FORMAT</span><br />
          <code>---<br />

            layout: archive<span class="hint"> Archive Page Layout</span> <br />
            title: String <span class="hint">Title of the webpage</span><br />
            permalink: / String / <span class="hint">CASE-SENSITIVE(SAME AS THE CATEGORY FIELD) Permalink for the webpage</span><br />
            tagline: String <span class="hint">  Tagline for the page</span><br />  
            category : String <span class="hint"> CASE SENSITIVE (SAME AS PERMALINK FIELD) Name of the category of which the page will show posts.</span><br />
            ---
        </code><br />
        </div>
        <div class="example">

          <code>---<br />
          layout: archive<br />
          title:  "Design"<br />
          permalink : "/Design"<br />
          category: "Design"<br />
          tagline: "It's all about perception."<br />
          ---
        </code>
      </div><br />
    </div>
  </p>
  </div>
  </div>
