---
layout: profile
title: Profile
permalink: profile
---

<div class='w-full h-100px absolute top-0 left-[50%] flex justify-center'>
  <img class="  w-44 h-44 mb-3 rounded-full shadow-lg" src="{{site.baseurl}}/assets/img/me.png" alt="Bonnie image"/>
</div>
<div class="dark w-full max-w-sm border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
   
    <div class="flex justify-end px-4 pt-4">
        <button id="dropdownButton" data-dropdown-toggle="dropdown" class="inline-block text-gray-500 dark:text-gray-400 hover:bg-gray-100 dark:hover:bg-gray-700 focus:ring-4 focus:outline-none focus:ring-gray-200 dark:focus:ring-gray-700 rounded-lg text-sm p-1.5" type="button">
            <span class="sr-only">Open dropdown</span>
            <svg class="w-6 h-6" aria-hidden="true" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M6 10a2 2 0 11-4 0 2 2 0 014 0zM12 10a2 2 0 11-4 0 2 2 0 014 0zM16 12a2 2 0 100-4 2 2 0 000 4z"></path></svg>
        </button>
<!--         <!-- Dropdown menu -->
        <div id="dropdown" class="z-10 hidden text-base list-none bg-white divide-y divide-gray-100 rounded-lg shadow w-44 dark:bg-gray-700">
            <ul class=" list-none py-2" aria-labelledby="dropdownButton">
            <li>
                <a href="#" class="no-underline block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100 dark:hover:bg-gray-600 dark:text-gray-200 dark:hover:text-white">Edit</a>
            </li>
            <li>
                <a href="#" class=" no-underline block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100 dark:hover:bg-gray-600 dark:text-gray-200 dark:hover:text-white">Export Data</a>
            </li>
            <li>
                <a href="#" class="no-underline block px-4 py-2 text-sm text-red-600 hover:bg-gray-100 dark:hover:bg-gray-600 dark:text-gray-200 dark:hover:text-white">Delete</a>
            </li>
            </ul>
        </div>
    </div> 
    <div class="dark flex flex-col items-center pb-10">
       
        <h5 class="mb-1 text-xl font-medium text-gray-900 dark:text-white">Jonas Walden</h5>
        <span class="text-sm text-gray-500 dark:text-gray-400">Developer</span>
        <span class="text-sm text-gray-500 dark:text-gray-400">Website.com</span>
        <div class="flex mt-4 space-x-3 md:mt-6">
            <a href="#" class="inline-flex items-center px-4 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-green-300 dark:bg-green-600 dark:hover:bg-green-700 dark:focus:ring-blue-green">Phone</a>
            <a href="#" class="inline-flex items-center px-4 py-2 text-sm font-medium text-center text-gray-900 bg-white border border-gray-300 rounded-lg hover:bg-gray-100 focus:ring-4 focus:outline-none focus:ring-red-200 dark:bg-red-800 dark:text-white dark:border-red-600 dark:hover:bg-red-700 dark:hover:border-red-700 dark:focus:ring-red-700">Mail</a>
        </div>
    </div>
</div>


