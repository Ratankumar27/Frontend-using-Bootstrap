# Frontend-using-Bootstrap

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />

</head>
<body>
  <p>
    This webpage uses modern technologies like Bootstrap and Font Awesome to create a clean, responsive design with interactive features such as modals, carousels, and tabbed content.
  </p>
  <p>
    The layout adapts smoothly across devices, providing easy navigation, clear course highlights, curriculum details, and a user-friendly FAQ section.
  </p>

  <p><h2>Technologies Used:</h2> HTML5 for structure, Bootstrap 5 for layout and components, Font Awesome for icons, and Google Fonts for typography.</p>

  <p><strong>Head Section:</strong> Links to CSS files and sets viewport for responsiveness.</p>

  <p><strong>Modals:</strong> Two pop-up forms for enquiries and demo bookings, triggered by buttons.</p>

  <p><strong>Navbar:</strong> Responsive menu with logo and navigation links; includes offcanvas menu for mobile.</p>

  <p><strong>Carousel Slider:</strong> A 3-image Bootstrap carousel with indicators and arrows for navigation.</p>

  <p><strong>Second Header:</strong> Shows logo plus WhatsApp and call buttons, arranged using Bootstrap grid.</p>

  <p><strong>Hero Section:</strong> Two-column layout with marketing headline, bullet points, CTAs on the left, and booking form on the right.</p>

  <p><strong>Counter Section:</strong> Displays key statistics in a shadowed grid format.</p>

  <p><strong>Key Highlights Section:</strong> Six cards showcasing course features, responsive grid (3/2/1 columns depending on screen size), with icons and descriptions.</p>

  <p><strong>Curriculum Section:</strong> Tab navigation with five tabs; each tab shows content in a styled box with two columns of bullet points (currently placeholder content). Tabs are scrollable on mobile.</p>

  <p><strong>Responsive Design:</strong> Layout adapts across devices—stacking on mobile, grids on tablet and desktop.</p>

  <p><strong>FAQ Accordion:</strong> Expandable questions where only one answer is visible at a time for better user experience.</p>

   <section>
   <img src="https://github.com/Ratankumar27/Frontend-using-Bootstrap/blob/fe46da49964652def624f6244dc48fc25cdf6abe/Screenshot%202025-06-11%20125119.png"/>
     
  <h2>📄 Brief Code Overview</h2>

  <h3>1. Head Section</h3>
  <ul>
    <li>Includes links to:
      <ul>
        <li>Bootstrap CSS</li>
        <li>Custom CSS (style.css, media.css)</li>
        <li>Font Awesome</li>
        <li>Google Fonts (Inter)</li>
      </ul>
    </li>
    <li>Configures viewport for responsive behavior.</li>
  </ul>

  <h3>2. Modals</h3>
  <ul>
    <li>🔹 Enquiry Modal (#enModal)
      <ul>
        <li>Form with Name, Email, and Mobile Number fields.</li>
        <li>Promotes free class booking.</li>
      </ul>
    </li>
    <li>🔹 Book Demo Modal (#bookDemo)
      <ul>
        <li>Simpler form for demo class booking.</li>
        <li>Triggered by relevant buttons.</li>
      </ul>
    </li>
  </ul>

  <h3>3. Navbar</h3>
  <ul>
    <li>Responsive navigation bar with:
      <ul>
        <li>Brand logo</li>
        <li>Links: Home, About, Course</li>
        <li>Offcanvas menu for mobile, toggled via hamburger icon.</li>
      </ul>
    </li>
  </ul>

  <h3>4. Carousel Slider</h3>
  <ul>
    <li>Bootstrap-based carousel with 3 images:
      <ul>
        <li>banner1.jpg, banner2.jpg, banner3.jpg</li>
      </ul>
    </li>
    <li>Navigation via indicators and arrows.</li>
  </ul>

  <h3>5. Second Header</h3>
  <ul>
    <li>Displays logo and two buttons:
      <ul>
        <li>WhatsApp Chat</li>
        <li>Call Us</li>
      </ul>
    </li>
    <li>Positioned using Bootstrap grid (left: logo, right: buttons).</li>
  </ul>

  <h3>6. Main Content (Hero Section)</h3>
  <ul>
    <li>Split into two columns:
      <ul>
        <li><strong>Left:</strong>
          <ul>
            <li>Headline highlighting “Digital Marketing”</li>
            <li>Bullet points with check icons</li>
            <li>CTA Buttons: Book Demo, Download Curriculum</li>
          </ul>
        </li>
        <li><strong>Right:</strong>
          <ul>
            <li>Free class booking form (same as modal)</li>
          </ul>
        </li>
      </ul>
    </li>
    <img src="https://github.com/Ratankumar27/Frontend-using-Bootstrap/blob/829062ebb31a3a5db944b747911a500f1191edeb/Screenshot%202025-06-11%20125504.png"/>
  </ul>

  <h3>7. Counter Section</h3>
  <ul>
    <li>Displays 5 statistic blocks:
      <ul>
        <li>Students Trained</li>
        <li>Starting Salary</li>
        <li>Recruiting Partners</li>
        <li>Program Timing</li>
        <li>Next Batch Start Date</li>
      </ul>
    </li>
    <li>Styled with Bootstrap grid and shadow.</li>
  </ul>

  <section>
    <h2>🟨 1. "Key Highlights of the Course" Section</h2>
    <h4>✅ Visual Overview:</h4>
    <ul>
      <li>Title: “Key Highlights of the Course”</li>
      <li>Subtitle: Placeholder description</li>
      <li>Six highlight cards arranged in a grid:
        <ul>
          <li>Desktop: 3 cards per row</li>
          <li>Tablet: 2 cards per row</li>
          <li>Mobile: 1 card per row</li>
        </ul>
      </li>
      <li>Each Card Includes:
        <ul>
          <li>Icon/image on the left</li>
          <li>Title and brief description on the right</li>
          <li>Styled with shadow, padding, and rounded corners</li>
        </ul>
      </li>
    </ul>
  </section>

  <section>
    <h2>🟩 2. "Curriculum" Section with Tab Navigation</h2>
    <h4>✅ Visual Overview:</h4>
    <ul>
      <li>Centered Heading: “Curriculum of Our Digital Marketing”</li>
      <li>Subheading: Placeholder text</li>
      <li>5 Horizontal Tabs:
        <ul>
          <li>Introduction</li>
          <li>Studies</li>
          <li>Google AdSense</li>
          <li>SEO Mastery</li>
          <li>Google Analytics</li>
        </ul>
      </li>
    </ul>

  <h4>🧠 Tab Behavior:</h4>
  <ul>
    <li>Clicking a tab slides in the corresponding content.</li>
    <li>Tab content box:
      <ul>
        <li>White background</li>
        <li>Rounded corners</li>
        <li>Shadow effect</li>
        <li>Two columns of bullet points with green check icons</li>
      </ul>
    </li>
    <li><em>Note:</em> Currently, all tab contents are placeholder items.</li>
  </ul>

  <h4>📱 Responsive Design:</h4>
  <ul>
    <li><strong>Mobile:</strong>
      <ul>
        <li>Cards stack vertically</li>
        <li>Tabs become scrollable</li>
      </ul>
    </li>
    <li><strong>Tablet:</strong>
      <ul>
        <li>2-column card layout</li>
        <li>Single-line tab layout</li>
      </ul>
    </li>
    <li><strong>Desktop:</strong>
      <ul>
        <li>3-column card layout</li>
        <li>Full-width tab layout</li>
      </ul>
    </li>
  </ul>
  <img src="https://github.com/Ratankumar27/Frontend-using-Bootstrap/blob/f2ae9123999bb574291d12fedba9a0156cecec9d/Screenshot%202025-06-11%20125311.png" />
  </section>

  <section>
    <h2>🧩 FAQ Accordion Structure</h2>
    <ul>
      <li>Each FAQ block includes:
        <ul>
          <li>Question: Toggle button</li>
          <li>Answer: Reveals on expansion</li>
        </ul>
      </li>
      <li>Only one item can be expanded at a time using:
        <ul>
          <li><code>data-bs-parent="#accordionExample"</code></li>
        </ul>
      </li>
    </ul>
    <img src="https://github.com/Ratankumar27/Frontend-using-Bootstrap/blob/4a31f7837728efb978c76ac9342333a1cb24a30a/Screenshot%202025-06-11%20125602.png"/>
  </section>
  </section> 
</body>
</html>
