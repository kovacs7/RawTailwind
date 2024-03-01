IGNORE THIS FILE

npm init -y -->package.json file --> can edit <script> for custom commands
npm i -D prettier-plugin-tailwindcss --> adds a devDependencies --> organise class in order for grp development.
.gitignore --> to ignore node_modules in our git repo
in package.json --> add new script --> npx prettier --write **/*.html
to run script --> npm run name_in_script
emojipedia for copy-paste emoji
&#9776; for hamburger icon --> unicode-table
shift alt downArrow --> repeat
items-center --> on one horizontal line
remember the row col media its very useful
don't forget to use sticky for navbar
never forget scroll-smooth

<section class="flex justify-center h-screen items-center">
      <div class="flex flex-col text-3xl gap-4 cursor-pointer">
        <a href="#rockets">Our Rockets</a>
        <a href="#testimonials">Testimonials</a>
        <a href="#contact">Contact Us</a>
      </div>
    </section>






<form action="" class="max-w-4xl mx-auto text-2xl sm:text-3xl flex flex-col items-left
            gap-4">
            <label for="subject">Subject:</label>
            <input type="text" id="subject" name="subject" required minlength="3" maxlength="50" placeholder="Your Subject" class="w-full text-black text-2xl sm:text-3xl p-3 rounded-xl border border-solid border-slate-900 dark:border-none"/>
            <label for="message">Message:</label>
            <textarea name="message" id="message" cols="30" rows="10" placeholder="Your Message" required class="w-full text-black text-2xl sm:text-3xl p-3 rounded-xl border border-solid border-slate-900 dark:border-none"></textarea>
            <button class="bg-teal-700 hover:bg-teal-600 active:bg-teal-500 text-white p-3 w-48 rounded-xl border border-solid border-slate-900 dark:border-none">Submit</button>
            </form>