<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MindEase</title>
  <style>
    body {
      margin: 0;
      font-family:"Times New Roman",serif;
      background-color: #e6f4f1;
      color: #1a2e35;
    }
    .container {
      width: 90%;
      max-width: 1100px;
      margin: auto;
      padding: 20px;
    }
    .hero {
      text-align: center;
      padding: 60px 20px;
      background-color:#e6f4f1; /* Slightly darker shade */
      transition: 0.3s ease-in-out; /* Smooth transition */
    }
    .hero img {
      width: 120px;
      height: auto;
      margin-bottom: 20px;
    }
    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 1.2rem;
      margin-bottom: 30px;
    }
    .hero button {
      padding: 12px 24px;
      font-size: 1rem;
      background-color: #4bb7ac;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }
    .section {
      margin-top: 60px;
    }
    .section h2 {
      font-size: 1.8rem;
      margin-bottom: 20px;
    }
    .services, .experts {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }
    .card {
      background: white;
      border-radius: 12px;
      padding: 20px;
      flex: 1 1 250px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }
.experts {
    display: flex;
    flex-wrap: nowrap; /* Prevents cards from wrapping */
    justify-content: space-between; /* Creates even spacing */
}
    .experts img {
      width: 80px;
      height: 80px;
      border-radius: 50%;
      object-fit: cover;
    }
.experts .card {
    text-align: center; /* Centers text inside the expert cards */

    flex: 1 1 30%; /* Adjusts width so all 3 fit */

}
    form {
      background: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      max-width: 400px;
      margin-top: 30px;
    }
    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border-radius: 6px;
      border: 1px solid #ccc;
    }
    form button {
      width: 100%;
      padding: 12px;
      background-color: #4bb7ac;
      color: white;
      font-size: 1rem;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="hero">
      <img src="C:\Users\hemna\Downloads\Untitled design.png" alt="MindEase logo" style="width:200px; height:200px; border-radius:50%;">
      <h1>MindEase</h1>
      <p>Talk to someone. Feel better.</p>
      <button>Get Started</button>
    </div>
<div class="section">
  <h2>About MindEase</h2>
  <div class="services">
<div class="card">
<p style="font-size: 20px;">
At MindEase, we believe mental wellness should be accessible,affordable,and stigma-free. That's why we've created a platform that connects individuals with licensed psychologists and certified therapists online-from the comfort of their homes. Whether you're dealing with anxiety,depression,trauma,stress,or just need someone to talk to,we are here for you.
</p>
</div>
<div class="section">
  <h2>About the Service</h2>
  <div class="services">
    <div class="card">Customised Therapy Package</div>
    <div class="card">Burnout Prevention & Work Life Balance Coaching</div>
    <div class="card">Exam, Stress & Performance Anxiety Therapy</div>
    <div class="card">ReLearn Intimacy Program</div>
    <div class="card">AI Driven Chat Support</div>
  </div>
</div>

<div class="section">
  <h2>How it Works</h2>
  <div class="services">
    <div class="card">Fill out a brief questionnaire</div>
    <div class="card">Get matched with a counselor</div>
    <div class="card">Start your session</div>
  </div>
</div>

<div class="section">
  <h2>Meet the Experts</h2>
  <div class="experts">
    <div class="card">
      <img src="C:\Users\hemna\OneDrive\Desktop\WhatsApp Image 2025-04-17 at 06.55.13_fec0f496.jpg" alt="Dr. Ananya Mehta">
      <p><strong>Dr. Ananya Mehta</strong><br><br>Clinical Psychologist<br><br>10-years experience.<br>Specializes,in mental counselling.<br>griet counselling,and<br> stress management</p>
    </div>
    <div class="card">
      <img src="C:\Users\hemna\OneDrive\Desktop\raghay.jpg" alt="Raghay Menon">
      <p><strong>Raghay Menon</strong><br><br>Counseling Psychologist<br><br>7-years experience.<br>Expert in oyuth counseling.<br>work-life balance,<br>and emotional wellbeing.</p>
    </div>
    <div class="card">
      <img src="C:\Users\hemna\OneDrive\Desktop\priya.jpg" alt="Priya Shah">
      <p><strong>Priya Shah</strong><br><br>Therapist & Cognitive<br>Behavioral Expert<br><br>Focus on trauma recovery,<br>relationship therapy,and<br>mindfuinces</p>
    </div>
  </div>
</div>

<div class="section">
  <h2>Get Matched with a Counselor</h2>
  <form>
    <input type="text" placeholder="Name" required />
    <input type="number" placeholder="Age" required />
    <input type="text" placeholder="City" required />
    <input type="text" placeholder="What mental health issue are you facing? " required />
    <input type="text" placeholder="How long have you been suffering?" required />
    <input type="text" placeholder="Have you consulted before?" required />
    <button type="submit">Submit & Get Matched</button>
  </form>
</div>


  </div>
</body>
</html># my-file
contains MindEase code
