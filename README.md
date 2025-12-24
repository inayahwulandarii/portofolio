<!DOCTYPE html>
<html lang="en" class="scroll-smooth dark">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=0" />
    <title>Inayah's Portfolio | Web Developer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
    <script>
      tailwind.config = {
        darkMode: 'class',
        theme: {
          extend: {
            colors: {
              primary: {
                light: '#3b82f6',
                dark: '#2563eb',
              },
              secondary: {
                light: '#10b981',
                dark: '#059669',
              },
            },
            animation: {
              'fade-in': 'fadeIn 0.5s ease-in-out',
              'slide-up': 'slideUp 0.5s ease-out',
            },
            keyframes: {
              fadeIn: {
                '0%': { opacity: '0' },
                '100%': { opacity: '1' },
              },
              slideUp: {
                '0%': { transform: 'translateY(20px)', opacity: '0' },
                '100%': { transform: 'translateY(0)', opacity: '1' },
              },
            },
          },
        },
      };
    </script>
    <style>
      .gradient-text {
        background-clip: text;
        -webkit-background-clip: text;
        color: transparent;
      }
      .light .gradient-text {
        background-image: linear-gradient(45deg, #27064e, #6210b9);
      }
      .dark .gradient-text {
        background-image: linear-gradient(45deg, #60a5fa, #34d399);
      }
      .project-card {
        transition: all 0.3s ease;
      }
      .project-card:hover {
        transform: translateY(-5px);
      }
      .theme-toggle {
        transition: all 0.3s ease;
      }
      .theme-toggle:hover {
        transform: rotate(30deg);
      }
      .nav-link {
        position: relative;
      }
      .nav-link::after {
        content: '';
        position: absolute;
        width: 0;
        height: 2px;
        bottom: -2px;
        left: 0;
        background-color: currentColor;
        transition: width 0.3s ease;
      }
      .nav-link:hover::after {
        width: 100%;
      }
    </style>
    <style>
      *,
      ::before,
      ::after {
        --tw-border-spacing-x: 0;
        --tw-border-spacing-y: 0;
        --tw-translate-x: 0;
        --tw-translate-y: 0;
        --tw-rotate: 0;
        --tw-skew-x: 0;
        --tw-skew-y: 0;
        --tw-scale-x: 1;
        --tw-scale-y: 1;
        --tw-pan-x: ;
        --tw-pan-y: ;
        --tw-pinch-zoom: ;
        --tw-scroll-snap-strictness: proximity;
        --tw-gradient-from-position: ;
        --tw-gradient-via-position: ;
        --tw-gradient-to-position: ;
        --tw-ordinal: ;
        --tw-slashed-zero: ;
        --tw-numeric-figure: ;
        --tw-numeric-spacing: ;
        --tw-numeric-fraction: ;
        --tw-ring-inset: ;
        --tw-ring-offset-width: 0px;
        --tw-ring-offset-color: #fff;
        --tw-ring-color: rgb(59 130 246 / 0.5);
        --tw-ring-offset-shadow: 0 0 #0000;
        --tw-ring-shadow: 0 0 #0000;
        --tw-shadow: 0 0 #0000;
        --tw-shadow-colored: 0 0 #0000;
        --tw-blur: ;
        --tw-brightness: ;
        --tw-contrast: ;
        --tw-grayscale: ;
        --tw-hue-rotate: ;
        --tw-invert: ;
        --tw-saturate: ;
        --tw-sepia: ;
        --tw-drop-shadow: ;
        --tw-backdrop-blur: ;
        --tw-backdrop-brightness: ;
        --tw-backdrop-contrast: ;
        --tw-backdrop-grayscale: ;
        --tw-backdrop-hue-rotate: ;
        --tw-backdrop-invert: ;
        --tw-backdrop-opacity: ;
        --tw-backdrop-saturate: ;
        --tw-backdrop-sepia: ;
        --tw-contain-size: ;
        --tw-contain-layout: ;
        --tw-contain-paint: ;
        --tw-contain-style: ;
      }
      ::backdrop {
        --tw-border-spacing-x: 0;
        --tw-border-spacing-y: 0;
        --tw-translate-x: 0;
        --tw-translate-y: 0;
        --tw-rotate: 0;
        --tw-skew-x: 0;
        --tw-skew-y: 0;
        --tw-scale-x: 1;
        --tw-scale-y: 1;
        --tw-pan-x: ;
        --tw-pan-y: ;
        --tw-pinch-zoom: ;
        --tw-scroll-snap-strictness: proximity;
        --tw-gradient-from-position: ;
        --tw-gradient-via-position: ;
        --tw-gradient-to-position: ;
        --tw-ordinal: ;
        --tw-slashed-zero: ;
        --tw-numeric-figure: ;
        --tw-numeric-spacing: ;
        --tw-numeric-fraction: ;
        --tw-ring-inset: ;
        --tw-ring-offset-width: 0px;
        --tw-ring-offset-color: #fff;
        --tw-ring-color: rgb(59 130 246 / 0.5);
        --tw-ring-offset-shadow: 0 0 #0000;
        --tw-ring-shadow: 0 0 #0000;
        --tw-shadow: 0 0 #0000;
        --tw-shadow-colored: 0 0 #0000;
        --tw-blur: ;
        --tw-brightness: ;
        --tw-contrast: ;
        --tw-grayscale: ;
        --tw-hue-rotate: ;
        --tw-invert: ;
        --tw-saturate: ;
        --tw-sepia: ;
        --tw-drop-shadow: ;
        --tw-backdrop-blur: ;
        --tw-backdrop-brightness: ;
        --tw-backdrop-contrast: ;
        --tw-backdrop-grayscale: ;
        --tw-backdrop-hue-rotate: ;
        --tw-backdrop-invert: ;
        --tw-backdrop-opacity: ;
        --tw-backdrop-saturate: ;
        --tw-backdrop-sepia: ;
        --tw-contain-size: ;
        --tw-contain-layout: ;
        --tw-contain-paint: ;
        --tw-contain-style: ;
      } /* ! tailwindcss v3.4.17 | MIT License | https://tailwindcss.com */
      *,
      ::after,
      ::before {
        box-sizing: border-box;
        border-width: 0;
        border-style: solid;
        border-color: #e5e7eb;
      }
      ::after,
      ::before {
        --tw-content: '';
      }
      :host,
      html {
        line-height: 1.5;
        -webkit-text-size-adjust: 100%;
        -moz-tab-size: 4;
        tab-size: 4;
        font-family: ui-sans-serif, system-ui, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
        font-feature-settings: normal;
        font-variation-settings: normal;
        -webkit-tap-highlight-color: transparent;
      }
      body {
        margin: 0;
        line-height: inherit;
      }
      hr {
        height: 0;
        color: inherit;
        border-top-width: 1px;
      }
      abbr:where([title]) {
        -webkit-text-decoration: underline dotted;
        text-decoration: underline dotted;
      }
      h1,
      h2,
      h3,
      h4,
      h5,
      h6 {
        font-size: inherit;
        font-weight: inherit;
      }
      a {
        color: inherit;
        text-decoration: inherit;
      }
      b,
      strong {
        font-weight: bolder;
      }
      code,
      kbd,
      pre,
      samp {
        font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, 'Liberation Mono', 'Courier New', monospace;
        font-feature-settings: normal;
        font-variation-settings: normal;
        font-size: 1em;
      }
      small {
        font-size: 80%;
      }
      sub,
      sup {
        font-size: 75%;
        line-height: 0;
        position: relative;
        vertical-align: baseline;
      }
      sub {
        bottom: -0.25em;
      }
      sup {
        top: -0.5em;
      }
      table {
        text-indent: 0;
        border-color: inherit;
        border-collapse: collapse;
      }
      button,
      input,
      optgroup,
      select,
      textarea {
        font-family: inherit;
        font-feature-settings: inherit;
        font-variation-settings: inherit;
        font-size: 100%;
        font-weight: inherit;
        line-height: inherit;
        letter-spacing: inherit;
        color: inherit;
        margin: 0;
        padding: 0;
      }
      button,
      select {
        text-transform: none;
      }
      button,
      input:where([type='button']),
      input:where([type='reset']),
      input:where([type='submit']) {
        -webkit-appearance: button;
        background-color: transparent;
        background-image: none;
      }
      :-moz-focusring {
        outline: auto;
      }
      :-moz-ui-invalid {
        box-shadow: none;
      }
      progress {
        vertical-align: baseline;
      }
      ::-webkit-inner-spin-button,
      ::-webkit-outer-spin-button {
        height: auto;
      }
      [type='search'] {
        -webkit-appearance: textfield;
        outline-offset: -2px;
      }
      ::-webkit-search-decoration {
        -webkit-appearance: none;
      }
      ::-webkit-file-upload-button {
        -webkit-appearance: button;
        font: inherit;
      }
      summary {
        display: list-item;
      }
      blockquote,
      dd,
      dl,
      figure,
      h1,
      h2,
      h3,
      h4,
      h5,
      h6,
      hr,
      p,
      pre {
        margin: 0;
      }
      fieldset {
        margin: 0;
        padding: 0;
      }
      legend {
        padding: 0;
      }
      menu,
      ol,
      ul {
        list-style: none;
        margin: 0;
        padding: 0;
      }
      dialog {
        padding: 0;
      }
      textarea {
        resize: vertical;
      }
      input::placeholder,
      textarea::placeholder {
        opacity: 1;
        color: #9ca3af;
      }
      [role='button'],
      button {
        cursor: pointer;
      }
      :disabled {
        cursor: default;
      }
      audio,
      canvas,
      embed,
      iframe,
      img,
      object,
      svg,
      video {
        display: block;
        vertical-align: middle;
      }
      img,
      video {
        max-width: 100%;
        height: auto;
      }
      [hidden]:where(:not([hidden='until-found'])) {
        display: none;
      }
      .container {
        width: 100%;
      }
      @media (min-width: 640px) {
        .container {
          max-width: 640px;
        }
      }
      @media (min-width: 768px) {
        .container {
          max-width: 768px;
        }
      }
      @media (min-width: 1024px) {
        .container {
          max-width: 1024px;
        }
      }
      @media (min-width: 1280px) {
        .container {
          max-width: 1280px;
        }
      }
      @media (min-width: 1536px) {
        .container {
          max-width: 1536px;
        }
      }
      .fixed {
        position: fixed;
      }
      .absolute {
        position: absolute;
      }
      .relative {
        position: relative;
      }
      .inset-0 {
        inset: 0px;
      }
      .z-50 {
        z-index: 50;
      }
      .mx-auto {
        margin-left: auto;
        margin-right: auto;
      }
      .mb-12 {
        margin-bottom: 3rem;
      }
      .mb-2 {
        margin-bottom: 0.5rem;
      }
      .mb-4 {
        margin-bottom: 1rem;
      }
      .mb-6 {
        margin-bottom: 1.5rem;
      }
      .mb-8 {
        margin-bottom: 2rem;
      }
      .ml-2 {
        margin-left: 0.5rem;
      }
      .mr-4 {
        margin-right: 1rem;
      }
      .mt-12 {
        margin-top: 3rem;
      }
      .mt-2 {
        margin-top: 0.5rem;
      }
      .mt-8 {
        margin-top: 2rem;
      }
      .block {
        display: block;
      }
      .flex {
        display: flex;
      }
      .inline-flex {
        display: inline-flex;
      }
      .grid {
        display: grid;
      }
      .hidden {
        display: none;
      }
      .h-16 {
        height: 4rem;
      }
      .h-2\.5 {
        height: 0.625rem;
      }
      .h-48 {
        height: 12rem;
      }
      .h-64 {
        height: 16rem;
      }
      .h-full {
        height: 100%;
      }
      .min-h-screen {
        min-height: 100vh;
      }
      .w-16 {
        width: 4rem;
      }
      .w-64 {
        width: 16rem;
      }
      .w-full {
        width: 100%;
      }
      .max-w-lg {
        max-width: 32rem;
      }
      @keyframes fadeIn {
        0% {
          opacity: 0;
        }
        100% {
          opacity: 1;
        }
      }
      .animate-fade-in {
        animation: fadeIn 0.5s ease-in-out;
      }
      @keyframes slideUp {
        0% {
          transform: translateY(20px);
          opacity: 0;
        }
        100% {
          transform: translateY(0);
          opacity: 1;
        }
      }
      .animate-slide-up {
        animation: slideUp 0.5s ease-out;
      }
      .grid-cols-1 {
        grid-template-columns: repeat(1, minmax(0, 1fr));
      }
      .grid-cols-2 {
        grid-template-columns: repeat(2, minmax(0, 1fr));
      }
      .flex-col {
        flex-direction: column;
      }
      .flex-wrap {
        flex-wrap: wrap;
      }
      .items-start {
        align-items: flex-start;
      }
      .items-center {
        align-items: center;
      }
      .justify-center {
        justify-content: center;
      }
      .justify-between {
        justify-content: space-between;
      }
      .gap-2 {
        gap: 0.5rem;
      }
      .gap-6 {
        gap: 1.5rem;
      }
      .gap-8 {
        gap: 2rem;
      }
      .space-x-3 > :not([hidden]) ~ :not([hidden]) {
        --tw-space-x-reverse: 0;
        margin-right: calc(0.75rem * var(--tw-space-x-reverse));
        margin-left: calc(0.75rem * calc(1 - var(--tw-space-x-reverse)));
      }
      .space-x-4 > :not([hidden]) ~ :not([hidden]) {
        --tw-space-x-reverse: 0;
        margin-right: calc(1rem * var(--tw-space-x-reverse));
        margin-left: calc(1rem * calc(1 - var(--tw-space-x-reverse)));
      }
      .space-x-6 > :not([hidden]) ~ :not([hidden]) {
        --tw-space-x-reverse: 0;
        margin-right: calc(1.5rem * var(--tw-space-x-reverse));
        margin-left: calc(1.5rem * calc(1 - var(--tw-space-x-reverse)));
      }
      .space-x-8 > :not([hidden]) ~ :not([hidden]) {
        --tw-space-x-reverse: 0;
        margin-right: calc(2rem * var(--tw-space-x-reverse));
        margin-left: calc(2rem * calc(1 - var(--tw-space-x-reverse)));
      }
      .space-y-4 > :not([hidden]) ~ :not([hidden]) {
        --tw-space-y-reverse: 0;
        margin-top: calc(1rem * calc(1 - var(--tw-space-y-reverse)));
        margin-bottom: calc(1rem * var(--tw-space-y-reverse));
      }
      .space-y-6 > :not([hidden]) ~ :not([hidden]) {
        --tw-space-y-reverse: 0;
        margin-top: calc(1.5rem * calc(1 - var(--tw-space-y-reverse)));
        margin-bottom: calc(1.5rem * var(--tw-space-y-reverse));
      }
      .overflow-hidden {
        overflow: hidden;
      }
      .scroll-smooth {
        scroll-behavior: smooth;
      }
      .rounded-full {
        border-radius: 9999px;
      }
      .rounded-lg {
        border-radius: 0.5rem;
      }
      .border {
        border-width: 1px;
      }
      .border-4 {
        border-width: 4px;
      }
      .border-gray-300 {
        --tw-border-opacity: 1;
        border-color: rgb(209 213 219 / var(--tw-border-opacity, 1));
      }
      .border-primary-light {
        --tw-border-opacity: 1;
        border-color: rgb(59 130 246 / var(--tw-border-opacity, 1));
      }
      .bg-gray-100 {
        --tw-bg-opacity: 1;
        background-color: rgb(243 244 246 / var(--tw-bg-opacity, 1));
      }
      .bg-gray-200 {
        --tw-bg-opacity: 1;
        background-color: rgb(229 231 235 / var(--tw-bg-opacity, 1));
      }
      .bg-gray-50 {
        --tw-bg-opacity: 1;
        background-color: rgb(249 250 251 / var(--tw-bg-opacity, 1));
      }
      .bg-primary-light {
        --tw-bg-opacity: 1;
        background-color: rgb(59 130 246 / var(--tw-bg-opacity, 1));
      }
      .bg-primary-light\/10 {
        background-color: rgb(59 130 246 / 0.1);
      }
      .bg-secondary-light {
        --tw-bg-opacity: 1;
        background-color: rgb(16 185 129 / var(--tw-bg-opacity, 1));
      }
      .bg-secondary-light\/10 {
        background-color: rgb(16 185 129 / 0.1);
      }
      .bg-transparent {
        background-color: transparent;
      }
      .bg-white {
        --tw-bg-opacity: 1;
        background-color: rgb(255 255 255 / var(--tw-bg-opacity, 1));
      }
      .bg-white\/80 {
        background-color: rgb(255 255 255 / 0.8);
      }
      .object-cover {
        object-fit: cover;
      }
      .p-2 {
        padding: 0.5rem;
      }
      .p-3 {
        padding: 0.75rem;
      }
      .p-6 {
        padding: 1.5rem;
      }
      .p-8 {
        padding: 2rem;
      }
      .px-3 {
        padding-left: 0.75rem;
        padding-right: 0.75rem;
      }
      .px-4 {
        padding-left: 1rem;
        padding-right: 1rem;
      }
      .px-6 {
        padding-left: 1.5rem;
        padding-right: 1.5rem;
      }
      .py-1 {
        padding-top: 0.25rem;
        padding-bottom: 0.25rem;
      }
      .py-12 {
        padding-top: 3rem;
        padding-bottom: 3rem;
      }
      .py-20 {
        padding-top: 5rem;
        padding-bottom: 5rem;
      }
      .py-3 {
        padding-top: 0.75rem;
        padding-bottom: 0.75rem;
      }
      .py-4 {
        padding-top: 1rem;
        padding-bottom: 1rem;
      }
      .pt-20 {
        padding-top: 5rem;
      }
      .text-center {
        text-align: center;
      }
      .text-2xl {
        font-size: 1.5rem;
        line-height: 2rem;
      }
      .text-3xl {
        font-size: 1.875rem;
        line-height: 2.25rem;
      }
      .text-4xl {
        font-size: 2.25rem;
        line-height: 2.5rem;
      }
      .text-lg {
        font-size: 1.125rem;
        line-height: 1.75rem;
      }
      .text-sm {
        font-size: 0.875rem;
        line-height: 1.25rem;
      }
      .text-xl {
        font-size: 1.25rem;
        line-height: 1.75rem;
      }
      .font-bold {
        font-weight: 700;
      }
      .font-medium {
        font-weight: 500;
      }
      .font-semibold {
        font-weight: 600;
      }
      .text-gray-500 {
        --tw-text-opacity: 1;
        color: rgb(107 114 128 / var(--tw-text-opacity, 1));
      }
      .text-gray-600 {
        --tw-text-opacity: 1;
        color: rgb(75 85 99 / var(--tw-text-opacity, 1));
      }
      .text-gray-800 {
        --tw-text-opacity: 1;
        color: rgb(31 41 55 / var(--tw-text-opacity, 1));
      }
      .text-primary-light {
        --tw-text-opacity: 1;
        color: rgb(59 130 246 / var(--tw-text-opacity, 1));
      }
      .text-secondary-light {
        --tw-text-opacity: 1;
        color: rgb(16 185 129 / var(--tw-text-opacity, 1));
      }
      .text-white {
        --tw-text-opacity: 1;
        color: rgb(255 255 255 / var(--tw-text-opacity, 1));
      }
      .opacity-10 {
        opacity: 0.1;
      }
      .shadow-lg {
        --tw-shadow: 0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1);
        --tw-shadow-colored: 0 10px 15px -3px var(--tw-shadow-color), 0 4px 6px -4px var(--tw-shadow-color);
        box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow);
      }
      .shadow-sm {
        --tw-shadow: 0 1px 2px 0 rgb(0 0 0 / 0.05);
        --tw-shadow-colored: 0 1px 2px 0 var(--tw-shadow-color);
        box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow);
      }
      .backdrop-blur-md {
        --tw-backdrop-blur: blur(12px);
        -webkit-backdrop-filter: var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity)
          var(--tw-backdrop-saturate) var(--tw-backdrop-sepia);
        backdrop-filter: var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity)
          var(--tw-backdrop-saturate) var(--tw-backdrop-sepia);
      }
      .transition-colors {
        transition-property: color, background-color, border-color, fill, stroke, -webkit-text-decoration-color;
        transition-property: color, background-color, border-color, text-decoration-color, fill, stroke;
        transition-property: color, background-color, border-color, text-decoration-color, fill, stroke, -webkit-text-decoration-color;
        transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
        transition-duration: 150ms;
      }
      .transition-opacity {
        transition-property: opacity;
        transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
        transition-duration: 150ms;
      }
      .transition-transform {
        transition-property: transform;
        transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
        transition-duration: 150ms;
      }
      .duration-300 {
        transition-duration: 300ms;
      }
      .hover\:scale-105:hover {
        --tw-scale-x: 1.05;
        --tw-scale-y: 1.05;
        transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
      }
      .hover\:bg-gray-100:hover {
        --tw-bg-opacity: 1;
        background-color: rgb(243 244 246 / var(--tw-bg-opacity, 1));
      }
      .hover\:bg-gray-200:hover {
        --tw-bg-opacity: 1;
        background-color: rgb(229 231 235 / var(--tw-bg-opacity, 1));
      }
      .hover\:underline:hover {
        -webkit-text-decoration-line: underline;
        text-decoration-line: underline;
      }
      .hover\:opacity-90:hover {
        opacity: 0.9;
      }
      .hover\:shadow-xl:hover {
        --tw-shadow: 0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1);
        --tw-shadow-colored: 0 20px 25px -5px var(--tw-shadow-color), 0 8px 10px -6px var(--tw-shadow-color);
        box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow);
      }
      .focus\:outline-none:focus {
        outline: 2px solid transparent;
        outline-offset: 2px;
      }
      .focus\:ring-2:focus {
        --tw-ring-offset-shadow: var(--tw-ring-inset) 0 0 0 var(--tw-ring-offset-width) var(--tw-ring-offset-color);
        --tw-ring-shadow: var(--tw-ring-inset) 0 0 0 calc(2px + var(--tw-ring-offset-width)) var(--tw-ring-color);
        box-shadow: var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow, 0 0 #0000);
      }
      .focus\:ring-primary-light:focus {
        --tw-ring-opacity: 1;
        --tw-ring-color: rgb(59 130 246 / var(--tw-ring-opacity, 1));
      }
      .dark\:block:is(.dark *) {
        display: block;
      }
      .dark\:hidden:is(.dark *) {
        display: none;
      }
      .dark\:border-gray-600:is(.dark *) {
        --tw-border-opacity: 1;
        border-color: rgb(75 85 99 / var(--tw-border-opacity, 1));
      }
      .dark\:border-primary-dark:is(.dark *) {
        --tw-border-opacity: 1;
        border-color: rgb(37 99 235 / var(--tw-border-opacity, 1));
      }
      .dark\:bg-gray-600:is(.dark *) {
        --tw-bg-opacity: 1;
        background-color: rgb(75 85 99 / var(--tw-bg-opacity, 1));
      }
      .dark\:bg-gray-700:is(.dark *) {
        --tw-bg-opacity: 1;
        background-color: rgb(55 65 81 / var(--tw-bg-opacity, 1));
      }
      .dark\:bg-gray-800:is(.dark *) {
        --tw-bg-opacity: 1;
        background-color: rgb(31 41 55 / var(--tw-bg-opacity, 1));
      }
      .dark\:bg-gray-900:is(.dark *) {
        --tw-bg-opacity: 1;
        background-color: rgb(17 24 39 / var(--tw-bg-opacity, 1));
      }
      .dark\:bg-gray-900\/80:is(.dark *) {
        background-color: rgb(17 24 39 / 0.8);
      }
      .dark\:bg-primary-dark:is(.dark *) {
        --tw-bg-opacity: 1;
        background-color: rgb(37 99 235 / var(--tw-bg-opacity, 1));
      }
      .dark\:bg-primary-dark\/10:is(.dark *) {
        background-color: rgb(37 99 235 / 0.1);
      }
      .dark\:bg-secondary-dark:is(.dark *) {
        --tw-bg-opacity: 1;
        background-color: rgb(5 150 105 / var(--tw-bg-opacity, 1));
      }
      .dark\:bg-secondary-dark\/10:is(.dark *) {
        background-color: rgb(5 150 105 / 0.1);
      }
      .dark\:text-gray-100:is(.dark *) {
        --tw-text-opacity: 1;
        color: rgb(243 244 246 / var(--tw-text-opacity, 1));
      }
      .dark\:text-gray-300:is(.dark *) {
        --tw-text-opacity: 1;
        color: rgb(209 213 219 / var(--tw-text-opacity, 1));
      }
      .dark\:text-primary-dark:is(.dark *) {
        --tw-text-opacity: 1;
        color: rgb(37 99 235 / var(--tw-text-opacity, 1));
      }
      .dark\:text-secondary-dark:is(.dark *) {
        --tw-text-opacity: 1;
        color: rgb(5 150 105 / var(--tw-text-opacity, 1));
      }
      .dark\:hover\:bg-gray-600:hover:is(.dark *) {
        --tw-bg-opacity: 1;
        background-color: rgb(75 85 99 / var(--tw-bg-opacity, 1));
      }
      .dark\:hover\:bg-gray-700:hover:is(.dark *) {
        --tw-bg-opacity: 1;
        background-color: rgb(55 65 81 / var(--tw-bg-opacity, 1));
      }
      .dark\:hover\:bg-gray-800:hover:is(.dark *) {
        --tw-bg-opacity: 1;
        background-color: rgb(31 41 55 / var(--tw-bg-opacity, 1));
      }
      .dark\:focus\:ring-primary-dark:focus:is(.dark *) {
        --tw-ring-opacity: 1;
        --tw-ring-color: rgb(37 99 235 / var(--tw-ring-opacity, 1));
      }
      @media (min-width: 768px) {
        .md\:mb-0 {
          margin-bottom: 0px;
        }
        .md\:flex {
          display: flex;
        }
        .md\:hidden {
          display: none;
        }
        .md\:h-80 {
          height: 20rem;
        }
        .md\:w-1\/2 {
          width: 50%;
        }
        .md\:w-1\/3 {
          width: 33.333333%;
        }
        .md\:w-2\/3 {
          width: 66.666667%;
        }
        .md\:w-80 {
          width: 20rem;
        }
        .md\:grid-cols-2 {
          grid-template-columns: repeat(2, minmax(0, 1fr));
        }
        .md\:grid-cols-4 {
          grid-template-columns: repeat(4, minmax(0, 1fr));
        }
        .md\:flex-row {
          flex-direction: row;
        }
        .md\:pl-12 {
          padding-left: 3rem;
        }
        .md\:pr-8 {
          padding-right: 2rem;
        }
        .md\:text-3xl {
          font-size: 1.875rem;
          line-height: 2.25rem;
        }
        .md\:text-6xl {
          font-size: 3.75rem;
          line-height: 1;
        }
      }
      @media (min-width: 1024px) {
        .lg\:grid-cols-3 {
          grid-template-columns: repeat(3, minmax(0, 1fr));
        }
      }
    </style>
  </head>
  <body class="light bg-gray-50 text-gray-800 dark:bg-gray-900 dark:text-gray-100 transition-colors duration-300">
    <!-- Header/Navigation -->
    <header class="fixed w-full z-50 bg-white/80 dark:bg-gray-900/80 backdrop-blur-md shadow-sm">
      <div class="container mx-auto px-6 py-4">
        <nav class="flex items-center justify-between">
          <a href="#" class="text-2xl font-bold gradient-text">Portfolio</a>

          <div class="hidden md:flex space-x-8">
            <a href="#home" class="nav-link">Home</a>
            <a href="#about" class="nav-link">About</a>
            <a href="#projects" class="nav-link">Projects</a>
            <a href="#skills" class="nav-link">Skills</a>
            <a href="#contact" class="nav-link">Contact</a>
          </div>

          <div class="flex items-center space-x-4">
            <button id="theme-toggle" class="theme-toggle p-2 rounded-full hover:bg-gray-200 dark:hover:bg-gray-700">
              <i class="fas fa-moon dark:hidden"></i>
              <i class="fas fa-sun hidden dark:block"></i>
            </button>

            <button id="mobile-menu-button" class="md:hidden p-2 rounded-full hover:bg-gray-200 dark:hover:bg-gray-700">
              <i class="fas fa-bars"></i>
            </button>
          </div>
        </nav>
      </div>

      <!-- Mobile Menu -->
      <div id="mobile-menu" class="hidden md:hidden bg-white dark:bg-gray-800 shadow-lg">
        <div class="container mx-auto px-6 py-4 flex flex-col space-y-4">
          <a href="#home" class="nav-link">Home</a>
          <a href="#about" class="nav-link">About</a>
          <a href="#projects" class="nav-link">Projects</a>
          <a href="#skills" class="nav-link">Skills</a>
          <a href="#contact" class="nav-link">Contact</a>
        </div>
      </div>
    </header>
    <!-- Hero Section -->
    <section id="home" class="min-h-screen flex items-center pt-20">
      <div class="container mx-auto px-6 py-20">
        <div class="flex flex-col md:flex-row items-center">
          <div class="md:w-1/2 mb-12 md:mb-0 animate-fade-in" style="opacity: 1; animation: 0.5s ease-in-out 0s 1 normal forwards running fadeIn; transform: translateY(0px)">
            <h1 class="text-4xl md:text-6xl font-bold mb-4">Hi, I'm <span class="gradient-text">Inayah</span></h1>
            <h2 class="text-2xl md:text-3xl font-semibold mb-6">Junior Software Engineer</h2>
            <p class="text-lg mb-8 text-gray-600 dark:text-gray-300 max-w-lg">I build exceptional digital experiences with modern web technologies. Focused on creating beautiful, functional, and user-friendly applications.</p>
            <div class="flex space-x-4">
              <a href="#contact" class="px-6 py-3 bg-primary-light dark:bg-primary-dark text-white rounded-lg hover:opacity-90 transition-opacity"> Contact Me </a>
              <a href="#projects" class="px-6 py-3 border border-gray-300 dark:border-gray-600 rounded-lg hover:bg-gray-100 dark:hover:bg-gray-800 transition-colors"> View Work </a>
            </div>
          </div>
          <div class="md:w-1/2 flex justify-center animate-slide-up" style="opacity: 1; transform: translateY(0px); animation: 0.5s ease-out 0s 1 normal forwards running slideUp">
            <div class="relative w-64 h-64 md:w-80 md:h-80 rounded-full overflow-hidden border-4 border-primary-light dark:border-primary-dark">
              <img src="https://i.imgur.com/tDGNu7d.jpeg" alt="Profile" class="w-full h-full object-cover" />
              <div class="absolute inset-0 bg-primary-light dark:bg-primary-dark opacity-10"></div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- About Section -->
    <section id="about" class="py-20 bg-gray-100 dark:bg-gray-800">
      <div class="container mx-auto px-6">
        <h2 class="text-3xl font-bold mb-12 text-center">About <span class="gradient-text">Me</span></h2>

        <div class="flex flex-col md:flex-row items-center">
          <div class="md:w-1/3 mb-8 md:mb-0 flex justify-center">
            <div class="w-64 h-64 rounded-lg overflow-hidden shadow-lg">
              <img src="https://i.imgur.com/zfcflwv.jpeg" alt="About" class="w-full h-full object-cover" />
            </div>
          </div>

          <div class="md:w-2/3 md:pl-12">
            <h3 class="text-2xl font-semibold mb-4">Who I Am</h3>
            <p class="mb-6 text-gray-600 dark:text-gray-300">
              I’m a Junior Software Engineer with more than 1 year of experience in building and maintaining web applications. I work with modern technologies and focus on writing clean, efficient, and reliable code. I’m passionate about
              learning, improving, and creating software that delivers real value to users.
            </p>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
              <div class="bg-white dark:bg-gray-700 p-6 rounded-lg shadow-sm">
                <div class="flex items-center mb-4">
                  <div class="p-3 rounded-full bg-primary-light/10 dark:bg-primary-dark/10 mr-4">
                    <i class="fas fa-graduation-cap text-primary-light dark:text-primary-dark"></i>
                  </div>
                  <h4 class="font-semibold">Education</h4>
                </div>
                <p class="text-gray-600 dark:text-gray-300">
                  Diploma in Computer Engineering<br />
                  Politeknik Negeri Sriwijaya, 2023
                </p>
              </div>

              <div class="bg-white dark:bg-gray-700 p-6 rounded-lg shadow-sm">
                <div class="flex items-center mb-4">
                  <div class="p-3 rounded-full bg-secondary-light/10 dark:bg-secondary-dark/10 mr-4">
                    <i class="fas fa-briefcase text-secondary-light dark:text-secondary-dark"></i>
                  </div>
                  <h4 class="font-semibold">Experience</h4>
                </div>
                <p class="text-gray-600 dark:text-gray-300">
                  Junior Software Engineer<br />
                  Educational Institution, 2024-Present
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Project Section -->
    <section id="projects" class="py-20">
      <div class="container mx-auto px-6">
        <h2 class="text-3xl font-bold mb-12 text-center">My <span class="gradient-text">Projects</span></h2>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
          <!-- Project 1 -->
          <div class="project-card bg-white dark:bg-gray-800 rounded-lg overflow-hidden shadow-lg hover:shadow-xl">
            <div class="h-48 overflow-hidden">
              <img
                src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?ixlib=rb-4.0.3&amp;ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&amp;auto=format&amp;fit=crop&amp;w=1170&amp;q=80"
                alt="Project 1"
                class="w-full h-full object-cover transition-transform duration-300 hover:scale-105"
              />
            </div>
            <div class="p-6">
              <h3 class="text-xl font-semibold mb-2">E-commerce Platform</h3>
              <p class="text-gray-600 dark:text-gray-300 mb-4">A full-featured online store with cart functionality, user authentication, and payment processing.</p>
              <div class="flex flex-wrap gap-2 mb-4">
                <span class="px-3 py-1 bg-gray-100 dark:bg-gray-700 rounded-full text-sm">HTML</span>
                <span class="px-3 py-1 bg-gray-100 dark:bg-gray-700 rounded-full text-sm">JavaScript</span>
                <span class="px-3 py-1 bg-gray-100 dark:bg-gray-700 rounded-full text-sm">CSS</span>
              </div>
              <div class="flex space-x-3">
                <a href="#" class="text-primary-light dark:text-primary-dark hover:underline">Live Demo</a>
                <a href="#" class="text-gray-500 hover:underline">Source Code</a>
              </div>
            </div>
          </div>

          <!-- Project 2 -->
          <div class="project-card bg-white dark:bg-gray-800 rounded-lg overflow-hidden shadow-lg hover:shadow-xl">
            <div class="h-48 overflow-hidden">
              <img
                src="https://images.unsplash.com/photo-1522542550221-31fd19575a2d?ixlib=rb-4.0.3&amp;ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&amp;auto=format&amp;fit=crop&amp;w=1170&amp;q=80"
                alt="Project 2"
                class="w-full h-full object-cover transition-transform duration-300 hover:scale-105"
              />
            </div>
            <div class="p-6">
              <h3 class="text-xl font-semibold mb-2">Task Management App</h3>
              <p class="text-gray-600 dark:text-gray-300 mb-4">A productivity application for organizing tasks with drag-and-drop functionality and team collaboration.</p>
              <div class="flex flex-wrap gap-2 mb-4">
                <span class="px-3 py-1 bg-gray-100 dark:bg-gray-700 rounded-full text-sm">HTML</span>
                <span class="px-3 py-1 bg-gray-100 dark:bg-gray-700 rounded-full text-sm">PHP</span>
                <span class="px-3 py-1 bg-gray-100 dark:bg-gray-700 rounded-full text-sm">CSS</span>
                <span class="px-3 py-1 bg-gray-100 dark:bg-gray-700 rounded-full text-sm">JavaScript</span>
              </div>
              <div class="flex space-x-3">
                <a href="#" class="text-primary-light dark:text-primary-dark hover:underline">Live Demo</a>
                <a href="#" class="text-gray-500 hover:underline">Source Code</a>
              </div>
            </div>
          </div>

          <!-- Project 3 -->
          <div class="project-card bg-white dark:bg-gray-800 rounded-lg overflow-hidden shadow-lg hover:shadow-xl">
            <div class="h-48 overflow-hidden">
              <img
                src="https://images.unsplash.com/photo-1467232004584-a241de8bcf5d?ixlib=rb-4.0.3&amp;ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&amp;auto=format&amp;fit=crop&amp;w=1169&amp;q=80"
                alt="Project 3"
                class="w-full h-full object-cover transition-transform duration-300 hover:scale-105"
              />
            </div>
            <div class="p-6">
              <h3 class="text-xl font-semibold mb-2">Weather Dashboard</h3>
              <p class="text-gray-600 dark:text-gray-300 mb-4">Real-time weather application with 5-day forecasts, location search, and interactive maps.</p>
              <div class="flex flex-wrap gap-2 mb-4">
                <span class="px-3 py-1 bg-gray-100 dark:bg-gray-700 rounded-full text-sm">JavaScript</span>
                <span class="px-3 py-1 bg-gray-100 dark:bg-gray-700 rounded-full text-sm">API Integration</span>
                <span class="px-3 py-1 bg-gray-100 dark:bg-gray-700 rounded-full text-sm">CSS3</span>
              </div>
              <div class="flex space-x-3">
                <a href="#" class="text-primary-light dark:text-primary-dark hover:underline">Live Demo</a>
                <a href="#" class="text-gray-500 hover:underline">Source Code</a>
              </div>
            </div>
          </div>
        </div>

        <div class="text-center mt-12">
          <a href="#" class="px-6 py-3 border border-gray-300 dark:border-gray-600 rounded-lg hover:bg-gray-100 dark:hover:bg-gray-800 transition-colors inline-flex items-center">
            View All Projects <i class="fas fa-arrow-right ml-2"></i>
          </a>
        </div>
      </div>
    </section>
    <!-- Skills Section -->
    <section id="skills" class="py-20 bg-gray-100 dark:bg-gray-800">
      <div class="container mx-auto px-6">
        <h2 class="text-3xl font-bold mb-12 text-center">My <span class="gradient-text">Skills</span></h2>

        <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
          <!-- Skill 1 -->
          <div class="bg-white dark:bg-gray-700 p-6 rounded-lg shadow-sm text-center">
            <div class="w-16 h-16 mx-auto mb-4 flex items-center justify-center bg-primary-light/10 dark:bg-primary-dark/10 rounded-full">
              <i class="fab fa-react text-3xl text-primary-light dark:text-primary-dark"></i>
            </div>
            <h3 class="font-semibold mb-2">React</h3>
            <div class="w-full bg-gray-200 dark:bg-gray-600 rounded-full h-2.5">
              <div class="bg-primary-light dark:bg-primary-dark h-2.5 rounded-full" style="width: 90%"></div>
            </div>
          </div>

          <!-- Skill 2 -->
          <div class="bg-white dark:bg-gray-700 p-6 rounded-lg shadow-sm text-center">
            <div class="w-16 h-16 mx-auto mb-4 flex items-center justify-center bg-primary-light/10 dark:bg-primary-dark/10 rounded-full">
              <i class="fab fa-js text-3xl text-primary-light dark:text-primary-dark"></i>
            </div>
            <h3 class="font-semibold mb-2">JavaScript</h3>
            <div class="w-full bg-gray-200 dark:bg-gray-600 rounded-full h-2.5">
              <div class="bg-primary-light dark:bg-primary-dark h-2.5 rounded-full" style="width: 95%"></div>
            </div>
          </div>

          <!-- Skill 3 -->
          <div class="bg-white dark:bg-gray-700 p-6 rounded-lg shadow-sm text-center">
            <div class="w-16 h-16 mx-auto mb-4 flex items-center justify-center bg-primary-light/10 dark:bg-primary-dark/10 rounded-full">
              <i class="fab fa-vuejs text-3xl text-primary-light dark:text-primary-dark"></i>
            </div>
            <h3 class="font-semibold mb-2">Vue.js</h3>
            <div class="w-full bg-gray-200 dark:bg-gray-600 rounded-full h-2.5">
              <div class="bg-primary-light dark:bg-primary-dark h-2.5 rounded-full" style="width: 85%"></div>
            </div>
          </div>

          <!-- Skill 4 -->
          <div class="bg-white dark:bg-gray-700 p-6 rounded-lg shadow-sm text-center">
            <div class="w-16 h-16 mx-auto mb-4 flex items-center justify-center bg-primary-light/10 dark:bg-primary-dark/10 rounded-full">
              <i class="fab fa-css3-alt text-3xl text-primary-light dark:text-primary-dark"></i>
            </div>
            <h3 class="font-semibold mb-2">CSS/Tailwind</h3>
            <div class="w-full bg-gray-200 dark:bg-gray-600 rounded-full h-2.5">
              <div class="bg-primary-light dark:bg-primary-dark h-2.5 rounded-full" style="width: 92%"></div>
            </div>
          </div>

          <!-- Skill 5 -->
          <div class="bg-white dark:bg-gray-700 p-6 rounded-lg shadow-sm text-center">
            <div class="w-16 h-16 mx-auto mb-4 flex items-center justify-center bg-secondary-light/10 dark:bg-secondary-dark/10 rounded-full">
              <i class="fab fa-node-js text-3xl text-secondary-light dark:text-secondary-dark"></i>
            </div>
            <h3 class="font-semibold mb-2">Node.js</h3>
            <div class="w-full bg-gray-200 dark:bg-gray-600 rounded-full h-2.5">
              <div class="bg-secondary-light dark:bg-secondary-dark h-2.5 rounded-full" style="width: 80%"></div>
            </div>
          </div>

          <!-- Skill 6 -->
          <div class="bg-white dark:bg-gray-700 p-6 rounded-lg shadow-sm text-center">
            <div class="w-16 h-16 mx-auto mb-4 flex items-center justify-center bg-secondary-light/10 dark:bg-secondary-dark/10 rounded-full">
              <i class="fas fa-database text-3xl text-secondary-light dark:text-secondary-dark"></i>
            </div>
            <h3 class="font-semibold mb-2">MongoDB</h3>
            <div class="w-full bg-gray-200 dark:bg-gray-600 rounded-full h-2.5">
              <div class="bg-secondary-light dark:bg-secondary-dark h-2.5 rounded-full" style="width: 75%"></div>
            </div>
          </div>

          <!-- Skill 7 -->
          <div class="bg-white dark:bg-gray-700 p-6 rounded-lg shadow-sm text-center">
            <div class="w-16 h-16 mx-auto mb-4 flex items-center justify-center bg-secondary-light/10 dark:bg-secondary-dark/10 rounded-full">
              <i class="fab fa-git-alt text-3xl text-secondary-light dark:text-secondary-dark"></i>
            </div>
            <h3 class="font-semibold mb-2">Git</h3>
            <div class="w-full bg-gray-200 dark:bg-gray-600 rounded-full h-2.5">
              <div class="bg-secondary-light dark:bg-secondary-dark h-2.5 rounded-full" style="width: 88%"></div>
            </div>
          </div>

          <!-- Skill 8 -->
          <div class="bg-white dark:bg-gray-700 p-6 rounded-lg shadow-sm text-center">
            <div class="w-16 h-16 mx-auto mb-4 flex items-center justify-center bg-secondary-light/10 dark:bg-secondary-dark/10 rounded-full">
              <i class="fas fa-mobile-alt text-3xl text-secondary-light dark:text-secondary-dark"></i>
            </div>
            <h3 class="font-semibold mb-2">Responsive Design</h3>
            <div class="w-full bg-gray-200 dark:bg-gray-600 rounded-full h-2.5">
              <div class="bg-secondary-light dark:bg-secondary-dark h-2.5 rounded-full" style="width: 95%"></div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Contact Section -->
    <section id="contact" class="py-20">
      <div class="container mx-auto px-6">
        <h2 class="text-3xl font-bold mb-12 text-center">Get In <span class="gradient-text">Touch</span></h2>

        <div class="flex flex-col md:flex-row">
          <div class="md:w-1/2 mb-12 md:mb-0 md:pr-8">
            <h3 class="text-2xl font-semibold mb-6">Contact Information</h3>
            <p class="mb-8 text-gray-600 dark:text-gray-300">Feel free to reach out to me for project inquiries, collaborations, or just to say hello. I'll get back to you as soon as possible.</p>

            <div class="space-y-6">
              <div class="flex items-start">
                <div class="p-3 rounded-full bg-primary-light/10 dark:bg-primary-dark/10 mr-4">
                  <i class="fas fa-envelope text-primary-light dark:text-primary-dark"></i>
                </div>
                <div>
                  <h4 class="font-semibold">Email</h4>
                  <p class="text-gray-600 dark:text-gray-300">inayahwhulandari01@gmail,com</p>
                </div>
              </div>

              <div class="flex items-start">
                <div class="p-3 rounded-full bg-primary-light/10 dark:bg-primary-dark/10 mr-4">
                  <i class="fas fa-phone-alt text-primary-light dark:text-primary-dark"></i>
                </div>
                <div>
                  <h4 class="font-semibold">Phone</h4>
                  <p class="text-gray-600 dark:text-gray-300">(+62) 82179412875</p>
                </div>
              </div>

              <div class="flex items-start">
                <div class="p-3 rounded-full bg-primary-light/10 dark:bg-primary-dark/10 mr-4">
                  <i class="fas fa-map-marker-alt text-primary-light dark:text-primary-dark"></i>
                </div>
                <div>
                  <h4 class="font-semibold">Location</h4>
                  <p class="text-gray-600 dark:text-gray-300">Palembang City, Indonesia</p>
                </div>
              </div>
            </div>

            <div class="mt-8">
              <h4 class="font-semibold mb-4">Follow Me</h4>
              <div class="flex space-x-4">
                <a href="https://github.com/inayahwulandarii" class="p-3 rounded-full bg-gray-100 dark:bg-gray-700 hover:bg-gray-200 dark:hover:bg-gray-600 transition-colors">
                  <i class="fab fa-github"></i>
                </a>
                <a href="https://www.linkedin.com/in/inayah-wulandarii/" class="p-3 rounded-full bg-gray-100 dark:bg-gray-700 hover:bg-gray-200 dark:hover:bg-gray-600 transition-colors">
                  <i class="fab fa-linkedin-in"></i>
                </a>
                <a href="https://x.com/onyournaya_" class="p-3 rounded-full bg-gray-100 dark:bg-gray-700 hover:bg-gray-200 dark:hover:bg-gray-600 transition-colors">
                  <i class="fab fa-twitter"></i>
                </a>
                <a href="https://www.instagram.com/inayahwulandarii/" class="p-3 rounded-full bg-gray-100 dark:bg-gray-700 hover:bg-gray-200 dark:hover:bg-gray-600 transition-colors">
                  <i class="fab fa-instagram"></i>
                </a>
              </div>
            </div>
          </div>

          <div class="md:w-1/2">
            <form class="bg-white dark:bg-gray-700 p-8 rounded-lg shadow-sm">
              <div class="mb-6">
                <label for="name" class="block mb-2 font-medium">Name</label>
                <input
                  type="text"
                  id="name"
                  class="w-full px-4 py-3 border border-gray-300 dark:border-gray-600 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary-light dark:focus:ring-primary-dark bg-transparent transition-colors"
                />
              </div>

              <div class="mb-6">
                <label for="email" class="block mb-2 font-medium">Email</label>
                <input
                  type="email"
                  id="email"
                  class="w-full px-4 py-3 border border-gray-300 dark:border-gray-600 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary-light dark:focus:ring-primary-dark bg-transparent transition-colors"
                />
              </div>

              <div class="mb-6">
                <label for="subject" class="block mb-2 font-medium">Subject</label>
                <input
                  type="text"
                  id="subject"
                  class="w-full px-4 py-3 border border-gray-300 dark:border-gray-600 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary-light dark:focus:ring-primary-dark bg-transparent transition-colors"
                />
              </div>

              <div class="mb-6">
                <label for="message" class="block mb-2 font-medium">Message</label>
                <textarea
                  id="message"
                  rows="5"
                  class="w-full px-4 py-3 border border-gray-300 dark:border-gray-600 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary-light dark:focus:ring-primary-dark bg-transparent transition-colors"
                ></textarea>
              </div>

              <button type="submit" class="w-full px-6 py-3 bg-primary-light dark:bg-primary-dark text-white rounded-lg hover:opacity-90 transition-opacity">Send Message</button>
            </form>
          </div>
        </div>
      </div>
    </section>
    <!-- Footer -->
    <footer class="bg-gray-100 dark:bg-gray-800 py-12">
      <div class="container mx-auto px-6">
        <div class="flex flex-col md:flex-row justify-between items-center">
          <div class="mb-6 md:mb-0">
            <a href="#" class="text-2xl font-bold gradient-text">Portfolio</a>
            <p class="mt-2 text-gray-600 dark:text-gray-300">© 2025 onyournaya</p>
          </div>

          <div class="flex space-x-6">
            <a href="#home" class="nav-link">Home</a>
            <a href="#about" class="nav-link">About</a>
            <a href="#projects" class="nav-link">Projects</a>
            <a href="#contact" class="nav-link">Contact</a>
          </div>
        </div>
      </div>
    </footer>
    <script>
      // Theme Toggle
      const themeToggle = document.getElementById('theme-toggle');
      const html = document.documentElement;

      // Check for saved user preference or use system preference
      const savedTheme = localStorage.getItem('theme') || (window.matchMedia('(prefers-color-scheme: dark)').matches ? 'dark' : 'light');
      html.classList.add(savedTheme);

      themeToggle.addEventListener('click', () => {
        html.classList.toggle('dark');
        const theme = html.classList.contains('dark') ? 'dark' : 'light';
        localStorage.setItem('theme', theme);
      });

      // Mobile Menu Toggle
      const mobileMenuButton = document.getElementById('mobile-menu-button');
      const mobileMenu = document.getElementById('mobile-menu');

      mobileMenuButton.addEventListener('click', () => {
        mobileMenu.classList.toggle('hidden');
      });

      // Close mobile menu when clicking on a link
      document.querySelectorAll('#mobile-menu a').forEach((link) => {
        link.addEventListener('click', () => {
          mobileMenu.classList.add('hidden');
        });
      });

      // Smooth scrolling for all links
      document.querySelectorAll('a[href^="#"]').forEach((anchor) => {
        anchor.addEventListener('click', function (e) {
          e.preventDefault();

          const targetId = this.getAttribute('href');
          if (targetId === '#') return;

          const targetElement = document.querySelector(targetId);
          if (targetElement) {
            window.scrollTo({
              top: targetElement.offsetTop - 80,
              behavior: 'smooth',
            });
          }
        });
      });

      // Add animation classes when elements come into view
      const animateOnScroll = () => {
        const elements = document.querySelectorAll('.animate-fade-in, .animate-slide-up');

        elements.forEach((element) => {
          const elementPosition = element.getBoundingClientRect().top;
          const screenPosition = window.innerHeight / 1.2;

          if (elementPosition < screenPosition) {
            element.style.opacity = '1';
            element.style.transform = 'translateY(0)';
          }
        });
      };

      // Set initial state for animated elements
      document.querySelectorAll('.animate-fade-in').forEach((el) => {
        el.style.opacity = '0';
        el.style.animation = 'fadeIn 0.5s ease-in-out forwards';
      });

      document.querySelectorAll('.animate-slide-up').forEach((el) => {
        el.style.opacity = '0';
        el.style.transform = 'translateY(20px)';
        el.style.animation = 'slideUp 0.5s ease-out forwards';
      });

      // Add scroll event listener
      window.addEventListener('scroll', animateOnScroll);
      // Trigger once on page load
      window.addEventListener('load', animateOnScroll);
    </script>
  </body>
</html>
