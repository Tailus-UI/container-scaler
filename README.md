# How to scale only the container not the content

A scale on the container and not on the content of a card when hovering.

Require Tailwind Css 2.2.16

    npm install -D tailwindcss@latest postcss@latest autoprefixer@latest

Enable JIT Compiler

    module.exports = {
        mode: 'jit',
        purge: {
            content : ['./templates/**/*.html'],
            safelist : []
        }
    }