---
layout: base.njk
title: contact
---
<section class="container" id="formCont">
    <div class="text">
        <h1>Contact Me</h1>
        <br>
        <p>
        In this form you can reach directly to me. whether if you have an idea to develop something, a project for any purpose or just say hello, All ideas or opinions are welcome here. When your mail arrives to me, I will answer to you as soon as I can.
        </p>
        <br>
        <p>
        Thank you :)
        </p>
    </div>
    <form name="contact" method="post" netlify>
        <div class="Mainform">
            <div class="Mainform__data">
                <label for="FirstName">First Name *</label>
                <input type="text" id="FirstName" name="FirstName" required>
            </div>
            <div class="Mainform__data">
                <label for="LastName">Last Name *</label>
                <input type="text" name="LastName" id="LastName" required>
            </div>
            <div class="Mainform__data">
                <label for="email">Email *</label>
                <input type="email" name="email" id="email" required>
            </div>
            <label for="message">Your Message Here *</label>
            <textarea name="message" id="message" required></textarea>
            <div class="Mainform__button">
                <button type="submit" class="btn btn--primary">Send</button>
                <button type="reset" class="btn btn--neutral">Clear</button>
            </div>
        </div>
    </form>
</section>