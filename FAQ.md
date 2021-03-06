---
title: FAQ
layout: default
nav: true
nav-order: 4
questions:
  - question: How can I subscribe to your mailing list?
    answer: You can subscribe <a href="https://mailman.ic.ac.uk/mailman/listinfo/stoic-talk" target="_blank">here</a>.
  - question: How can I keep up-to-date?
    answer: By subscribing to our <a href="https://mailman.ic.ac.uk/mailman/listinfo/stoic-talk" target="_blank">mailing list</a> or by joining the ICTV <a href="https://www.facebook.com/groups/ictv1617/" target="_blank">facebook group. </a>  
  - question: Do you hold meetings?
    answer: We aim to hold a meeting once or twice a week. We advertise the date on the mailing list.
  - question: How much commitment is expected from a member?
    answer: It's completely up to you how much of your time you'd like to commit; we ask nothing from you. ICTV mainly exists as an outlet for you to create content (that goes up on our media/social channels).
  - question: I have a script for a short film; can I find people interested in making it at ICTV?
    answer: Yes, there's a high chance that you will. Get in touch.
  - question:  I have an idea for an ICTV project, but I don’t have much experience; what can I do?
    answer: Get in touch with us! We'll see if we can try and help you turn your idea into reality.
  - question:  What equipment do you have and what are the hire rates?
    answer: You can find a partial list <a href="https://drive.google.com/open?id=0BzsQuDveh0kzVnlMSDR5MG9DczA">here</a>. For more, get in touch.
  - question: I want something filmed; can you do it for free?
    answer: We film for hire; however, if you think that your project/event would be of benefit for ICTV to film, then there could be chance that we would film it for free, but ICTV would own all the footage. Get in touch to discuss.
  - question: >
      I am not a member, but I would like to hire equipment; how can I go about that?
    answer: >
      If you are not an Imperial Student, then you can only hire equipment at the non-member rate. To hire equipment, we need to be informed two weeks in advance. Conditions of hire can be found <a href="https://drive.google.com/open?id=0BzsQuDveh0kzZjAwOVRGMnhuRHc">here </a>.
      <br><br>If you are an Imperial Student, then there are two ways you can go about that:
      <ul><li>1. Buy ICTV membership and hire at the member rate;</li><li>2. Hire at the non-member rate.</li></ul>
      Get in touch with us at  <a href="mailto:ictv@imperial.ac.uk" target="_top">ictv [at] imperial.ac.uk</a>.
  - question: >
      Can I borrow equipment for free?
    answer: >
      No, but if you are a member <strong>actively</strong> involved with ICTV, then you can borrow equipment for free for no more than two consecutive days at a time. Actively involved means participating in ICTV filming projects, attending ICTV meeting, and/or making contributions of your time for the development of ICTV.
  - question: >
      How can I book the shared studio?
    answer: >
      The shared studio is managed by the <a href="https://union.ic.ac.uk/media/mediagroup/">media group</a>. If you are a member, then you can request a booking <a href="https://room-bookings.media.su.ic.ac.uk/">here</a>. You need to have a media account to log in. You get a media account automtically if you log in to any of the machines in the media hub.
  - question: >
       I am an active member of ICTV; how can I book equipment?
    answer: >
      You can do so <a href="https://imperialcollege.tv/bookings/">here</a>.
  - question: Who are the current committee members?
    answer: You can find an up-to-date list <a href="https://www.imperialcollegeunion.org/activities/a-to-z/382">here</a>.
  - question: >
       I am a student, but not an Imperial College student; can I still join?
    answer: >
      Some external students can join ICTV. In order to do so, you would need to get an Imperial College Union associate membership. After you get that, you can buy ICTV membership from the Union website. You can find more details <a href=" https://www.imperialcollegeunion.org/your-union/how-were-run/membership">here</a> about obtaining an associate membership from Imperial College Union. If you encounter any issues, do get in touch with us.
---




<div class="panel-group" id="accordion" role="tablist" aria-multiselectable="true">
{% for item in page.questions %}
  <div class="panel panel-default">
    <div class="panel-heading" role="tab" id="heading{{ forloop.index}}">
      <h4 class="panel-title">
        <a class="collapsed" role="button" data-toggle="collapse" data-parent="#accordion" href="#q{{ forloop.index }}" aria-expanded="false" aria-controls="q{{ forloop.index }}">
        <strong>{{ item.question }}</strong>
        </a>
      </h4>
    </div>
    <div id="q{{ forloop.index }}" class="panel-collapse collapse" role="tabpanel" aria-labelledby="heading{{forloop.index}}">
      <div class="panel-body">
        {{ item.answer }}
      </div>
    </div>
  </div>

{% endfor %}


</div>





