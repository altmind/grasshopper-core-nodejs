---
title: Authentication Examples
uuid: core-auth-example
---
// Basic Authentication Example
grasshopper.auth( 'basic', { username: '', password: '' } ).then( function( token ) {
    // Store user's token somewhere
} ).done();


// Google Authentication Example
grasshopper.auth( 'google', { code: 'TMP GOOGLE TOKEN' } ).then( function( token ) {
    // Store user's token somewhere
} ).done();