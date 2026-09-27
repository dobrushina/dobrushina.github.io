---
layout: about
permalink: /Training
title: Training for mental health professionals
description: Neuroscience-informed, neurodiversity-affirming psychotherapy training for mental health professionals.
profile:
  align: right
  image: profile.jpg
published: true
---


I teach neuroscience-informed, neurodiversity-affirming psychotherapy: therapy that puts the wellbeing of neurodivergent people themselves first, rather than trying to make them seem more ‘normal’ to others. My workshops help therapists adapt formulation, technique and the therapeutic relationship to the needs of autistic, ADHD and otherwise neurodivergent clients.
{: .lead}

<section id="meeting-the-needs" class="training-card">
  <p class="training-label">Next workshop · Online</p>
  <h3>Working Therapeutically with Neurodivergent Clients: Meeting the Needs</h3>

  <dl class="training-facts">
    <div>
      <dt>When</dt>
      <dd>Thu 28 January 2027, 09:30–14:00 GMT</dd>
    </div>
    <div>
      <dt>Where</dt>
      <dd>Online, hosted by University of Strathclyde</dd>
    </div>
    <div>
      <dt>Can't make it live?</dt>
      <dd>Recording available after the workshop</dd>
    </div>
  </dl>

  <table class="training-prices">
    <tr><th scope="row">Early bird</th><td>£100, until Friday 18 December 2026</td></tr>
    <tr><th scope="row">Standard</th><td>£120</td></tr>
    <tr><th scope="row">Reduced</th><td>£60, for students, trainees, NHS Band 5 and below, and equivalent third-sector roles</td></tr>
  </table>

  <div class="training-booking">
    <a class="training-button" href="https://onlineshop.strath.ac.uk/conferences-and-events/humanities-and-social-sciences-faculty/school-of-education/working-therapeutically-with-neurodivergent-clients-meeting-the-needs">Book your place</a>
    <small>Booking is handled by the University of Strathclyde online shop.</small>
  </div>

  <h4>Why this workshop</h4>
  <p>Up to 20% of the population is neurodivergent. Neurodivergence often sits behind resistant depression, anxiety, PTSD, or what gets diagnosed as ‘personality disorders’, and neurodivergent clients, diagnosed or not, often fail to benefit from therapy that isn’t adjusted to their needs. The double empathy problem and limited training can strain the therapeutic relationship and worsen outcomes.</p>
  <p>We will look at contemporary approaches to neurodiversity and the neuroscience behind clinical presentations, so you can build more accurate, neurodiversity-informed formulations and adapt your work to clients’ cognitive, sensory and communication needs.</p>

  <h4>You will be able to</h4>
  <ul class="training-list">
    <li>Apply transdiagnostic and neurodiversity-affirming frameworks to clinical formulation</li>
    <li>Identify the distinct mechanisms and needs behind mental health difficulties in neurodivergent people</li>
    <li>Adjust psychotherapeutic techniques to cognitive, sensory and communication needs</li>
    <li>Reduce misunderstanding and strengthen the therapeutic alliance across neurotypes</li>
  </ul>

  <h4>Who it’s for</h4>
  <p>Psychologists, counsellors, psychotherapists, medical professionals, social workers, occupational therapists, nurse therapists and other allied health practitioners, at any career stage.</p>

  {% if site.data.trainings.quotes.size > 0 %}
  <h4>What participants say</h4>
  {% for quote in site.data.trainings.quotes %}
  <blockquote>
    <p>{{ quote.text }}</p>
    <p class="training-attribution">— {{ quote.attribution }}</p>
  </blockquote>
  {% endfor %}
  {% endif %}
</section>

{% if site.data.trainings.upcoming_polish.size > 0 %}
<section>
  <h3>Also coming up · in Polish</h3>
  <ul class="training-list">
    {% for event in site.data.trainings.upcoming_polish %}
    <li><a href="{{ event.url }}"><strong>{{ event.title }}</strong></a><br>{{ event.date }} · {{ event.organiser }}, {{ event.location }}</li>
    {% endfor %}
  </ul>
</section>
{% endif %}

<section>
  <h3>Watch on demand</h3>
  <ul class="training-list">
    {% for course in site.data.trainings.on_demand %}
    <li><a href="{{ course.url }}"><strong>{{ course.title }}</strong></a><br>{{ course.description }}</li>
    {% endfor %}
  </ul>
</section>

<section>
  <h3>About me</h3>
  <p>I am a counselling psychologist (HCPC), an advanced accredited schema therapist (ISST), and Clinical Director of the Laboratory for Innovation in Autism at the University of Strathclyde. Neurodivergent myself, I have worked with autistic and ADHD clients for over ten years as a medical doctor, psychologist and team leader, and my research on how emotion regulation is grounded in the body shapes what I teach. More about my <a href="/Research">research</a>.</p>
</section>

<section>
  <h3>Previous trainings</h3>
  <p>Over 1,000 professionals across the UK, Europe, North America and Australia have attended my training.</p>
  {% for group in site.data.trainings.previous %}
  <h4>{{ group.year }}</h4>
  <ul class="training-list">
    {% for item in group.items %}
    <li><strong>{{ item.title }}</strong><br>{{ item.details }}</li>
    {% endfor %}
  </ul>
  {% endfor %}
  <p><small>Earlier, 2016–2024: workshops on psychotherapy with neurodivergent clients, neurotechnology in mental healthcare, quantitative EEG, and rehabilitation for children with brain tumours.</small></p>
</section>

<section class="panel training-mailing">
  <h3>Hear about new trainings first</h3>
  <p>A short, occasional email for healthcare professionals. <a href="http://eepurl.com/i1SuY2">Join the mailing list</a></p>
</section>
