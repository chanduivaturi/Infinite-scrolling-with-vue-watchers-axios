# infinite-scrolling-with-vue-watchers-axios
Infinite Scrolling in Vue with asynchronous loading through Watchers/Axios to add more info
            <hr>
            <h6>Methods:</h6>
            <ul>
                <li>
                    We Define our methods using the methods member. Methods allow us create functions and bind events to these functions as well as handle these events. In the scrollCheck() function, we use three properties<span class="text-info">(window.scrollY, window.innerHeight, document.documentElement.offsetHeight)</span> to manually create our infinite scroll feature:
                </li>
                <li>
                    <b>loadPosts():</b> is core part of the application which load posts from a open source JSON API Sever using <span class="text-danger">AXIOS</span>
                </li>
                <li>
                    <b>resetData():</b> To reset all the selected options from Controls section
                </li>
            </ul>
            <hr>
            <h6>Watchers:</h6>
            <ul>
                <li>We created one watch member,so that when ever the data in <span class="text-danger">endOfTheScreen</span> watches for changes to the state of the app and updates the DOM accordingly
                </li>
            </ul>
            <hr>
            <h6>Created:</h6>
            <ul>
                <li>Since the processing of the options is finished you have access to reactive data properties and change them if you want</li>
            </ul>
            <hr>
            <h6>Controls:</h6>
            <ul>
                <li><b>Disable/Enable Auto Loading:</b> You want to disable/enable auto loading of posts using direct button control(Incase if you want to save users internet from loading posts unneccessarily)</li>
                <li><b>Select Limit:</b> You can limit No of Posts you want to get as response</li>
                <li><b>Load Posts:</b> Direct loading of posts based on selected controls</li>
                <li><b>Reset Everything:</b> To reset all your controls to actual without reloading</li>
            </ul>
