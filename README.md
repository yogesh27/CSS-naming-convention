# css-naming-conventions
This includes naming convention which can be used to give class names for maintaining css in a better way.
This is based on:
1. BEM css principle
2. Linkedin and Css styling

Use below naming conventions:
1. moduleName--element__state (moduleName-module2--element__state, module2 can be btn, drp, radio, chk, chkgrp)
2. camelCase for module name
3. -- : for --title, --label, --value, --item, --border, --list (verb)
4. __ : for color, state like __active, __inactive, __focus, __empty, __full etc (attribute)
5. moduleName-module2: can have elements to it like moduleName-othermModule--element__state

Examples:   

1. <div class="tweet">
        <h3 class="tweet--counter">1</h3>
        <h3 class="tweet--title">My Tweet title</h3>        
        <p class="tweet--content">Tweet content goes here...</p>
        <p class="tweet--content__maxLength">Sorry...! You tweets exceeds 140 characters. </p>
        <p class="tweet--content__empty">This is empty tweet. </p>
        <button class="btn tweet-btn--addTweet"></span>
        <button class="btn tweet-btn--deleteTweet"></span>
        <button class="btn tweet-btn--deleteTweet__disable"></span>
        <button class="btn tweet-btn--deleteTweet__hide"></span>
    </div>

2. <div class="pageHeader">
        <span class="pageHeader--title">
            My Projects
        </span>
        <button class="btn pageHeader-btn--addProject">+ Add</button>
    </div>
    
    
    
 ------- will keep on adding more naming -------
