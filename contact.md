---
layout: page
title: Contact
---

<div class='container contact'>
  <h2 class='contact--header'>Contact</h2>

  <form
    class="contact-page col-sm-10 col-sm-offset-1"
    action="https://formspree.io/moqkbeap" 
    method="POST"
  >
    <div class="form-group row">
      <label>
        Name
        <input
          type="text" 
          name="name" 
          class="col-sm-10 form-control" 
          id="nameInput" 
          placeholder="Name"
        >
      </label>
    </div>
    <div class="form-group row">
      <label>
        Email
        <input
          type="email" 
          class="form-control" 
          id="emailInput" 
          placeholder="Email Address"
        >
      </label>
    </div>
    <div class="form-group row">
      <label>
        Comment or Message
        <textarea 
          class="form-control" 
          type="text" 
          name="text" 
          rows="5"
          placeholder="Message"
        >
        </textarea>
      </label>
    </div>
    <div class='row'>
      <button
        type="submit" 
        value="Send" 
        class="btn contact--button"
      >
        Submit
      </button>
    </div>
  </form>
</div>