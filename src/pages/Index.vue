<template>
  <Layout>
    <div class="hero container-inner mx-auto flex flex-col sm:flex-row justify-between py-16">
      <div class="text-4xl font-bold w-full sm:w-3/5 text-center sm:text-left">
        <div class="leading-tight">Consultancy</div>
        <div class="text-green-700 leading-tight">Code</div>
        <div class="text-green-700 leading-tight">Content</div>
        <div class="text-green-700 leading-tight">Photography</div>
        <div class="text-green-700 leading-tight">Video</div>
      </div>
      <div class="mt-8 sm:mt-0">
        <g-image src="../../static/content.svg" alt="hero" class="mx-auto sm:mx-0" />
      </div>
    </div> <!-- end hero -->

    <div class="container-inner mx-auto">
      <p class="text-lg sm:text-xl">The web is a large and bewildering place, our business can help you get your ideas off the ground. We are here to help steer your ideas and deliver them online.</p>
     
      <p class="text-lg sm:text-xl">Content and data is the lifeblood of any successful business and with a broad range of experience across photography, content development (CMS) and Javascript coding, we can make that happen for you.</p>
     
      <div class="flex justify-between items-center py-6">
        <div class="w-full sm:w-1/2 px-8 py-8 sm:py-0">
          <g-image src="../../static/mind_map.svg" alt="browser" />
        </div>
        <div class="w-1/2 px-8 hidden sm:flex justify-end">
          <g-image src="../../static/code_review.svg" alt="mobile" />
        </div>
      </div>
    </div>

    <div class="overflow-x-hidden">
      <div class="projects container-inner mx-auto text-xl border-t border-gray-500 border-b py-16 mb-16 relative">
        <h2 class="font-bold mb-6" id="services">Here are some of the many services we can offer:</h2>

        <div class="absolute right-0" style="top: 50px; transform: translate(100%) rotate(180deg)">
          <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
        </div>

        <ul class="text-lg sm:text-xl">
          <li class="checkmark mb-6">
            <div>CMS/Web Development</div>
            <div class="text-lg text-gray-600">Content Management Systems need not be daunting and that is why we work with lightweight, easy to learn, simple to use systems that can help us collaborate. Take for example Netlify CMS and I am also a Javascript Developer, highly experienced with frameworks such as Vue and React.</div>
          </li>
          <li class="checkmark mb-6">
            <div>Content Writing</div>
            <div class="text-lg text-gray-600">My Wife and I both enjoy writing, so a lot of the writing Tina takes care of and she can help you put together great content for your website or other projects</div>
          </li>
          <li class="checkmark mb-6">
            <div>Photography</div>
            <div class="text-lg text-gray-600">Feel free to visit our other site, dedicated to the topic of photography <a href="https://nicklewis.photo">nicklewis.photo</a> but my photography skills also play a big part in delivering great content to our clients</div>
          </li>
          <li class="checkmark mb-6">
            <div>Social Media</div>
            <div class="text-lg text-gray-600">Social media has it's challenges but alongside traditional websites, is a critical part of any business's connection with it's audience. Naturally writing, photography and video skills come into play</div>
          </li>

        </ul>
      </div> <!-- end projects -->
      <div class="projects container-inner mx-auto text-xl border-t border-gray-500 border-b py-16 mb-16 relative">
        <h2 class="font-bold mb-6" id="projects">Projects:</h2>

        <div class="absolute right-0" style="top: 50px; transform: translate(100%) rotate(180deg)">
          <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
        </div>

        <ul class="text-lg sm:text-xl">
          <li class="checkmark mb-6">
            <div>nicklewis.photo</div>
            <div class="text-lg text-gray-600">Further up this page you will have seen me mention <a href="https://nicklewis.photo">nicklewis.photo</a> which is one of my projects with a distinct portfolio look and feel about it. There is a fairly lightweight blog there too. It was built using GatsbyJS and like all of my sites now, is hosted on Netlify in conjunction with the Sanity.io CMS (which is superb by the way).</div>
          </li>
          <!-- <li class="checkmark mb-6">
            <div>headforcode.com</div>
            <div class="text-lg text-gray-600">I have been working on the concepts for a project known as <a href="https://headforcode.com">headforcode.com</a> for a while and the aim will be to help people learn more about code, the art of coding and how you can achieve so much with something as ubiquitous as the browser you have on your computer or the phone in your pocket. So it will be a tutorial site with content you'd either subscribe to or donate to via Patreon. Decision to be made there. Oh and the website at the moment is a bit of a placeholder to be frank...</div>
          </li> -->
          <li class="checkmark mb-6">
            <div>Nfolio</div>
            <div class="text-lg text-gray-600">Many years ago I ran another version of a site I called Nfolio but I must have shut it down around 2010, if not before. I have recently rekindled the domain which I never closed and have started creating a new version at <a href="https://www.nfolio.com">nfolio.com</a>. I am building this site with Nuxt, Vue, Sanity and Netlify. It allows people to buy prints from my extensive range of photos, taken from Hampshire to Rome.</div>
          </li>
          <!-- <li class="checkmark mb-6">
            <div>Headforcode</div>
            <div class="text-lg text-gray-600">Lorem ipsum dolor sit amet consectetur adipisicing elit. Illum totam, ratione recusandae autem provident ea. Corrupti minus magnam nulla ad odio. Fugit magnam accusamus nisi incidunt! Dignissimos itaque eos ab.</div>
          </li> -->
          <li class="checkmark mb-6">
            <div>Bournemouth Jazz</div>
            <div class="text-lg text-gray-600">Built using the same tools as the site you are reading now, this new site is currently quite simple and it promotes a Jazz Club in Bournemouth. I will soon be adding forum features and helping the client write and publish new articles on their meetings and the history of Jazz music as a whole - <a href="https://bournemouthjazzclub.org">Bournemouth Swing and Big Band Jazz Club</a></div>
          </li>
          <li class="checkmark mb-6">
            <div>How about yours?</div>
            <div class="text-lg text-gray-600">Well - fill out the contact form today for a quotation and quick response from us!</div>
          </li>
        </ul>
      </div> <!-- end projects -->
    </div>

    <div class="overflow-x-hidden border-gray-200 border-b">
      <div class="get-to-know-me container-inner mx-auto text-xl pb-16 relative">
        <h2 class="font-bold mb-6" id="about">Get to know me:</h2>

        <div class="absolute left-0" style="top: 50px; transform: translateX(-100%)">
          <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
        </div>

        <div class="flex flex-col sm:flex-row justify-between items-center mb-16">
          <div><g-image src="../../static/profile.jpg" alt="avatar" class="w-32 h-32 rounded-full mb-8 lg:mb-0" /></div>
          <div class="flex-1 text-lg sm:text-xl ml-6">I am a freelance web developer, content creator and photographer, who is on a mission to help businesses and individuals build solutions for their online world.</div>
        </div>

        <!--<div class="responsive-container">
          <iframe class="responsive-iframe w-full h-full top-0 left-0 border-0" src="https://www.youtube.com/embed/uHo6o1TNQeE" style="border:0;" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>-->
      </div> <!-- end get-to-know me -->
    </div>

    <div class="overflow-x-hidden">
      <div class="contact-me bg-background-secondary pt-16">
        <div class="container-inner mx-auto text-xl pb-4 relative">
          <h2 class="font-bold mb-6" id="contact">Contact me:</h2>

          <div class="absolute right-0 top-0" style="transform: translate(100%) rotate(180deg)">
            <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
          </div>

          <!--<p class="mb-12">Static sites cannot submit forms on their own. However, services like <a href="https://www.netlify.com/docs/form-handling">Netlify Forms</a> or <a href="https://formspree.io">FormSpree</a> can help you do this without a backend.</p>-->

          <div class="text-lg sm:text-lg mb-16">
            <form 
              name="contact" 
              class="mb-12" 
              method="post" 
              v-on:submit.prevent="handleSubmit"
              data-netlify="true"
              data-netlify-honeypot="bot-field">
              <input type="hidden" name="form-name" value="contact" />
              <p hidden>
                <label>
                  Don’t fill this out: <input name="bot-field" />
                </label>
              </p>
              <div class="flex flex-wrap mb-6 -mx-4">
                  <div class="w-full md:w-1/2 mb-6 md:mb-0 px-4">
                      <label class="block mb-2 text-copy-primary" for="name">
                          Name
                      </label>

                      <input type="text" name="name" id="name" placeholder="Joe Bloggs" class="block w-full bg-background-form border border-border-color-primary shadow rounded outline-none focus:border-green-700 mb-2 p-4" 
                      v-model="formData.name"
                      required>
                  </div>

                  <div class="w-full px-4 md:w-1/2">
                      <label class="block text-copy-primary mb-2" for="email">
                          Email Address
                      </label>

                      <input type="email" name="email" id="email" placeholder="email@example.com"  class="block w-full bg-background-form border border-border-color-primary shadow rounded outline-none focus:border-green-700 mb-2 p-4" 
                       v-model="formData.email"
                      required>
                  </div>
              </div>

              <div class="w-full mb-12">
                  <label class="block text-copy-primary mb-2" for="message">
                      Message
                  </label>

                  <textarea id="message" rows="5" name="message" class="block w-full bg-background-form border border-border-color-primary shadow rounded outline-none appearance-none focus:border-green-700 mb-2 px-4 py-4" placeholder="Enter your message here." 
                  v-model="formData.message"
                  required></textarea>
              </div>

              <div class="flex justify-end w-full">
                  <button type="submit" value="submit" class="block bg-green-700 hover:bg-green-800 text-white text-sm font-semibold tracking-wide uppercase shadow rounded cursor-pointer px-6 py-3">Submit</button>
              </div>
          </form>
          </div>
        </div>
      </div> <!-- end contact-me -->
    </div>

    <!-- <div class="newsletter bg-background-tertiary">
      <div class="container-inner mx-auto py-16 pb-8 text-center textl-xl">
        <h2 class="text-2xl font-bold mb-8">Join my Newsletter</h2>

        <div class="w-4/5 mx-auto mb-8">
          <p class="mb-8 text-lg sm:text-xl">Errr, not just yet but there will be a newsletter at some point!</p>

          <form action="#">
            <div class="flex flex-col sm:flex-row">
              <input type="email" name="email" placeholder="Your email address" class="flex-1 bg-background-form rounded sm:rounded-r-none px-4 py-4 leading-normal border border-border-color-primary sm:border-r-0 shadow outline-none focus:border-green-700 z-10" required>
              <button data-element="submit" class="flex-2 w-40 uppercase bg-green-700 text-white rounded sm:rounded-l-none text-lg py-3 px-8 tracking-wide shadow focus:outline-none hover:bg-green-800 focus:bg-green-800 z-10 w-full sm:w-auto mt-4 sm:mt-0">
                <span>Subscribe</span>
              </button>
            </div>
          </form>
        </div>
      </div> -->

      <div class="container-inner mx-auto -mt-32 pb-4 overflow-x-hidden">
        <svg width="725" height="166" xmlns="http://www.w3.org/2000/svg"><g fill="none" fill-rule="evenodd"><g opacity=".515"><path d="M1.848 165.696a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm370 0a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zM20.326 162a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM75.76 162a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.52 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.305 3.696a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm370 0a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zM205.326 162a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.523 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.52 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696z" opacity=".503" fill="#2E855A"/></g><g opacity=".9"><g opacity=".515" fill="#2E855A"><path d="M1.848 147.696a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm370 0a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zM20.326 144a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM75.76 144a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.52 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.305 3.696a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm370 0a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zM205.326 144a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.523 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.52 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696z" opacity=".503"/></g></g><g opacity=".8"><g opacity=".515" fill="#2E855A"><path d="M1.848 129.696a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm370 0a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zM20.326 126a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM75.76 126a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.52 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.305 3.696a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm370 0a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zM205.326 126a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.523 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.52 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696z" opacity=".503"/></g></g><g opacity=".7"><g opacity=".515" fill="#2E855A"><path d="M1.848 111.696a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm370 0a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zM20.326 108a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM75.76 108a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.52 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.305 3.696a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm370 0a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zM205.326 108a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.523 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.52 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696z" opacity=".503"/></g></g><g opacity=".6"><g opacity=".515" fill="#2E855A"><path d="M1.848 93.696a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm370 0a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zM20.326 90a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM38.804 90a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM57.283 90a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM75.76 90a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM94.24 90a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.305 3.696a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm370 0a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zM205.326 90a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM260.76 90a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.52 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696z" opacity=".503"/></g></g><g opacity=".5"><g opacity=".515" fill="#2E855A"><path d="M1.848 75.696a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm370 0a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zM20.326 72a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM38.804 72a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM57.283 72a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM75.76 72a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM94.24 72a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.305 3.696a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm370 0a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zM205.326 72a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM260.76 72a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.52 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696z" opacity=".503"/></g></g><g opacity=".4"><g opacity=".515" fill="#2E855A"><path d="M1.848 57.696a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm370 0a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zM20.326 54a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM38.804 54a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM57.283 54a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM75.76 54a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM94.24 54a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.305 3.696a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm370 0a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zM205.326 54a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM260.76 54a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.52 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696z" opacity=".503"/></g></g><g opacity=".3"><g opacity=".515" fill="#2E855A"><path d="M1.848 39.696a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm370 0a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zM20.326 36a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM38.804 36a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM57.283 36a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM75.76 36a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM94.24 36a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.305 3.696a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm370 0a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zM205.326 36a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM260.76 36a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.52 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696z" opacity=".503"/></g></g><g opacity=".2"><g opacity=".515" fill="#1C75BC"><path d="M1.848 21.696a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm370 0a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zM20.326 18a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM38.804 18a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM57.283 18a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM75.76 18a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM94.24 18a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.305 3.696a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm370 0a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zM205.326 18a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM260.76 18a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.52 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.521 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm-351.522 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696z" opacity=".503"/></g></g><g opacity=".1"><g opacity=".515" fill="#2E855A"><path d="M1.848 3.696a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm370 0a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zM20.326 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM38.804 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM57.283 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM75.76 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM94.24 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM112.718 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM131.197 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM149.675 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM168.153 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM186.848 3.696a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zm370 0a1.848 1.848 0 1 1 0-3.696 1.848 1.848 0 0 1 0 3.696zM205.326 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM223.804 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM242.283 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM260.76 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM279.24 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM297.718 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM316.197 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM334.675 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zM353.153 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696zm370 0a1.848 1.848 0 1 1 0 3.696 1.848 1.848 0 0 1 0-3.696z" opacity=".503"/></g></g></g></svg>
      </div>
    <!-- </div> -->

  </Layout>
</template>

<script>
export default {
  data() {
    return {
      formData: {},
    }
  },
  methods: {
  encode(data) {
    return Object.keys(data)
      .map(key => encodeURIComponent(key) + '=' + encodeURIComponent(data[key]))
      .join('&')
  },
  handleSubmit(e) {
    fetch('/', {
      method: 'POST',
      headers: { 'Content-Type': 'application/x-www-form-urlencoded' },
      body: this.encode({
        'form-name': e.target.getAttribute('name'),
        ...this.formData,
      }),
    })
    .then(() => this.$router.push('/success'))
    .catch(error => alert(error))
  }
},

  metaInfo: {
    title: 'Home'
  }
}
</script>

