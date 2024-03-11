<template>
    <article
      class="p-4 bg-white rounded-lg shadow-xl place-content-center text-slate-800"
    >
      <header>
        <h1 class="pb-5 text-lg font-semibold"><slot name="header"></slot></h1>
      </header>
      <slot></slot>
    </article>
  </template>
/** . Slots are placeholders for specific dynamic content 
(components or text) that comes from the parent component. Slots are an excellent way to reuse 
templates and offer a lot of flexibility. C
*/