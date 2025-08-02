<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Qiddiya.Fit | Multilingual Fitness Hub</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet" />
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet" />
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
    integrity="sha512-papBMe5XlePbEcK+sR8F6+1Nw5GxMCG6sj+/0GmdtLYM7qF2LZgY4Yz1AwZlxS6k4z1Lj5PTMtjNpRocA9zh4g=="
    crossorigin="anonymous"
    referrerpolicy="no-referrer"
  />
  <style>
    body {
      font-family: 'Cairo', sans-serif;
      scroll-behavior: smooth;
    }
    header {
      background: linear-gradient(90deg, #2563eb 0%, #3b82f6 100%);
    }
    a {
      transition: color 0.3s ease;
    }
    a:hover {
      color: #bfdbfe; /* light blue */
    }
    button:hover {
      background-color: #1e40af; /* darker blue */
    }
    input:focus,
    textarea:focus {
      outline: none;
      border-color: #3b82f6;
      box-shadow: 0 0 5px #3b82f6;
    }
  </style>
</head>
<body class="bg-gray-50 text-gray-900">

  <header class="sticky top-0 z-50 shadow-lg">
    <div class="container mx-auto px-6 py-4 flex justify-between items-center">
      <h1 class="text-3xl font-extrabold text-white cursor-pointer select-none">Qiddiya.Fit</h1>
      <nav>
        <ul class="flex space-x-8 items-center text-white font-semibold text-lg">
          <li><a href="#home" class="hover:text-blue-200"><i class="fas fa-home mr-1"></i>Home</a></li>
          <li><a href="#about" class="hover:text-blue-200"><i class="fas fa-info-circle mr-1"></i>About</a></li>
          <li><a href="#blog" class="hover:text-blue-200"><i class="fas fa-blog mr-1"></i>Blog</a></li>
          <li><a href="#contact" class="hover:text-blue-200"><i class="fas fa-envelope mr-1"></i>Contact</a></li>
          <li>
            <select class="text-sm rounded p-1 bg-white text-gray-700 border border-gray-300" aria-label="Select Language">
              <option>العربية</option>
              <option selected>English</option>
              <option>Français</option>
              <option>中文</option>
            </select>
          </li>
        </ul>
      </nav>
    </div>
  </header>

  <main id="home" class="container mx-auto px-6 py-16">
    <section class="text-center mb-24">
      <img
        src="https://images.unsplash.com/photo-1571019613914-85f342c41f1b"
        alt="Fitness"
        class="w-full max-h-96 object-cover rounded-3xl mb-10 shadow-2xl mx-auto"
      />
      <h2 class="text-6xl font-extrabold mb-6 text-blue-700 drop-shadow-lg">Where Fitness Meets the Future</h2>
      <p class="text-2xl max-w-4xl mx-auto text-gray-700 leading-relaxed">
        Explore the latest in wellness, workouts, and health — in Arabic, English, French, and Chinese.
        Stay active. Stay Qiddiya.
      </p>
    </section>

    <section id="about" class="mb-24">
      <h3 class="text-4xl font-extrabold mb-8 text-blue-700 border-b-4 border-blue-400 inline-block pb-2">About Us</h3>
      <p class="text-xl leading-relaxed text-gray-800 max-w-4xl mx-auto">
        Qiddiya.Fit is a multilingual platform dedicated to health and fitness enthusiasts inspired by Saudi Arabia's groundbreaking Qiddiya project.
        We aim to empower a healthier lifestyle across cultures with inclusive content and global perspectives.
      </p>
    </section>

    <section id="blog" class="mb-24">
      <h3 class="text-4xl font-extrabold mb-10 text-blue-700 border-b-4 border-blue-400 inline-block pb-2">Latest Blog Posts</h3>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-12">
        <article
          class="bg-white rounded-3xl shadow-lg hover:shadow-2xl transition p-6 cursor-pointer transform hover:-translate-y-1 duration-300"
          tabindex="0"
          role="article"
          aria-label="Top Fitness Trends in 2025"
        >
          <img
            src="https://images.unsplash.com/photo-1605296867304-46d5465a13f1"
            alt="Workout Trends"
            class="w-full h-52 object-cover rounded-2xl mb-5"
            loading="lazy"
          />
          <h4 class="font-bold text-2xl mb-3 text-blue-800">Top Fitness Trends in 2025</h4>
          <p class="text-gray-700 text-base leading-relaxed">
            Explore what’s trending in workouts, gear, and training styles this year.
          </p>
        </article>
        <article
          class="bg-white rounded-3xl shadow-lg hover:shadow-2xl transition p-6 cursor-pointer transform hover:-translate-y-1 duration-300"
          tabindex="0"
          role="article"
          aria-label="Nutrition Tips for Busy Lifestyles"
        >
          <img
            src="https://images.unsplash.com/photo-1556911220-e15b29be8c25"
            alt="Nutrition"
            class="w-full h-52 object-cover rounded-2xl mb-5"
            loading="lazy"
          />
          <h4 class="font-bold text-2xl mb-3 text-blue-800">Nutrition Tips for Busy Lifestyles</h4>
          <p class="text-gray-700 text-base leading-relaxed">
            Smart eating strategies for people on the go — stay energized and fit.
          </p>
        </article>
        <article
          class="bg-white rounded-3xl shadow-lg hover:shadow-2xl transition p-6 cursor-pointer transform hover:-translate-y-1 duration-300"
          tabindex="0"
          role="article"
          aria-label="How Qiddiya is Shaping Future Athletes"
        >
          <img
            src="https://images.unsplash.com/photo-1600180758890-6b94519fdea3"
            alt="Qiddiya Athletes"
            class="w-full h-52 object-cover rounded-2xl mb-5"
            loading="lazy"
          />
          <h4 class="font-bold text-2xl mb-3 text-blue-800">How Qiddiya is Shaping Future Athletes</h4>
          <p class="text-gray-700 text-base leading-relaxed">
            Discover how Qiddiya is building a new generation of elite sports talent.
          </p>
        </article>
      </div>
    </section>

    <section id="contact" class="mb-20">
      <h3
        class="text-4xl font-extrabold mb-10 text-blue-700 border-b-4 border-blue-400 inline-block pb-2 text-center"
      >
        Contact Us
      </h3>
      <form
        class="bg-white p-10 rounded-3xl shadow-xl max-w-3xl mx-auto"
        novalidate
        onsubmit="return validateForm(event)"
      >
        <div class="mb-8">
          <label for="name" class="block mb-3 font-semibold text-gray-900">Your Name</label>
          <input
            type="text"
            id="name"
            name="name"
            class="w-full border border-gray-300 p-4 rounded-2xl"
            placeholder="Enter your full name"
            required
            minlength="3"
          />
        </div>
        <div class="mb-8">
          <label for="email" class="block mb-3 font-semibold text-gray-900">Email Address</label>
          <input
            type="email"
            id="email"
            name="email"
            class="w-full border border-gray-300 p-4 rounded-2xl"
            placeholder="Enter your email address"
            required
          />
        </div>
        <div class="mb-8">
          <label for="message" class="block mb-3 font-semibold text-gray-900">Your Message</label>
          <textarea
            id="message"
            name="message"
            class="w-full border border-gray-300 p-4 rounded-2xl h-40"
            placeholder="Write your message here..."
            required
            minlength="10"
          ></textarea>
        </div>
        <button
          type="submit"
          class="bg-blue-700 text-white px-12 py-4 rounded-2xl text-xl font-semibold hover:bg-blue-800 transition duration-300"
        >
          Send Message
        </button>
      </form>
    </section>
  </main>

  <footer class="bg-white text-center py-8 border-t border-gray-200">
    <p class="text-sm text-gray-600">&copy; 2025 Qiddiya.Fit — All rights reserved. | Designed for a global healthy future</p>
  </footer>

  <script>
    function validateForm(event) {
      const form = event.target;
      if (!form.checkValidity()) {
        form.reportValidity();
        event.preventDefault();
        return false;
      }
      alert('Thank you for contacting us! We will get back to you soon.');
      form.reset();
      event.preventDefault(); // Remove this to enable real form submission
      return true;
    }
  </script>

</body>
</html>
