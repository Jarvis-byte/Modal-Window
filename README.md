# Modal-Window
<h3>What is a Modal</h3>
<p>In user interface design for computer applications, a modal window is a graphical control element subordinate to an application's main window. 
  A modal window creates a mode that disables the main window but keeps it visible, with the modal window as a child window in front of it.</p>
  <br></br>
  <ul>
  <h3>How it works</h3>
  <li>
    Modals are built with HTML, CSS, and JavaScript. They’re positioned over everything else in the document and remove scroll from the <body> so that modal content scrolls instead.
  </li>
    <li>
    Clicking on the modal “backdrop” will automatically close the modal.
  </li> 
         <li>
Modals use position: fixed, which can sometimes be a bit particular about its rendering. Whenever possible, place your modal HTML in a top-level position to avoid potential interference from other elements. You’ll likely run into issues when nesting a .modal within another fixed element.
  </li>  
           <li>
Once again, due to position: fixed, there are some caveats with using modals on mobile devices. See our browser support docs for details.
  </li>
  </ul>
  
  
<a href="https://modal-view-v2.netlify.app"> Website Link<a/>
