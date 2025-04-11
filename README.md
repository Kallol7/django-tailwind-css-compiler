Update tailwind.config.js to point to the correct django project folder.
</br></br>
Project Structure:
<pre>
django-tailwind-css-compiler
├───myproject (Django project)
│   ├───app
│   │   └───templates
│   │       └───app
│   │           └───index.html
│   ├───templates
│   │   └───base.html
│   │       └───<script src="https://cdn.tailwindcss.com"></script>
│   └───manage.py
├───...
├───input.css
├───package.json
├───tailwind.config.js
└───...
</pre>
</br>
After running the following commands, <i><b>main.css</b></i> will be generated for you.
```sh
    git clone `https://github.com/your_repo` myproject
    npm run _install
    npm run build
```
