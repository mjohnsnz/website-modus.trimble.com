---
title: "Pagination"
layout: "single"
description: "Pagination affords navigation between pages of content, and it highlights the page currently in view."
components: true
images:
  - "/img/headers/components/pagination.png"
aliases:
  - "/elements/pagination/"
bootstrapURL: "/components/pagination/"
reactBootstrapURL: "/components/pagination/"
---

## Overview

Pagination allows the user to easily find and navigate through large amounts of content and breaks up content into multiple pages.

## Usage

**Use when**

- Amount of content will take a long time to load/render.
- If you want to browse the data by navigating through pages.
- A table contains more than 30 items.
- A page contains enough content to justify breaking it into smaller chunks to improve a user’s experience.

**Don’t use when**

- Using lazy load to load content as the user scrolls.

## Specifications

<table class="table table-bordered bg-white">
  <thead class="thead-light">
    <tr>
      <th></th>
      <th>Example</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">Small</th>
      <td class="anatomy-cell">
        <nav aria-label="...">
          <ul class="pagination pagination-sm anatomy-display-static" data-anatomy-colors="false" style="font-size: 12px">
            <li class="page-item">
              <a class="page-link" href="#">
                <i class="modus-icons">chevron_left</i>
              </a>
            </li>
            <li class="page-item">
              <a class="page-link" href="#">
                <i class="modus-icons">more_horizontal</i>
              </a>
            </li>
            <li class="page-item">
              <a class="page-link" href="#"> 3 </a>
            </li>
            <li class="page-item">
              <a class="page-link" href="#"> 4 </a>
            </li>
            <li class="page-item active" aria-current="page">
              <a class="page-link" href="#">5 <span class="sr-only">(current)</span></a>
            </li>
            <li class="page-item">
              <a class="page-link" href="#"> 6 </a>
            </li>
            <li class="page-item">
              <a class="page-link" href="#"> 7 </a>
            </li>
            <li class="page-item">
              <a class="page-link" href="#">
                <i class="modus-icons">more_horizontal</i>
              </a>
            </li>
            <li class="page-item">
              <a class="page-link" href="#">
                <i class="modus-icons">chevron_right</i>
              </a>
            </li>
          </ul>
        </nav>
        <nav aria-label="...">
          <ul class="pagination pagination-sm m-0 mt-5">
            <li class="page-item">
              <a href="#" class="page-link anatomy-display-static" data-anatomy-colors="false" data-anatomy-popover="false">1</a>
            </li>
          </ul>
        </nav>
      </td>
    </tr>
    <tr>
      <th scope="row">Default</th>
      <td class="anatomy-cell">
        <div>
          <nav aria-label="..." style="width: 300px">
            <ul class="pagination anatomy-display-static" data-anatomy-colors="false">
              <li class="page-item">
                <a class="page-link" href="#">
                  <i class="modus-icons">chevron_left</i>
                </a>
              </li>
              <li class="page-item">
                <a class="page-link" href="#">
                  <i class="modus-icons">more_horizontal</i>
                </a>
              </li>
              <li class="page-item">
                <a class="page-link" href="#"> 3 </a>
              </li>
              <li class="page-item">
                <a class="page-link" href="#"> 4 </a>
              </li>
              <li class="page-item active" aria-current="page">
                <a class="page-link" href="#">5 <span class="sr-only">(current)</span></a>
              </li>
              <li class="page-item">
                <a class="page-link" href="#"> 6 </a>
              </li>
              <li class="page-item">
                <a class="page-link" href="#"> 7 </a>
              </li>
              <li class="page-item">
                <a class="page-link" href="#">
                  <i class="modus-icons">more_horizontal</i>
                </a>
              </li>
              <li class="page-item">
                <a class="page-link" href="#">
                  <i class="modus-icons">chevron_right</i>
                </a>
              </li>
            </ul>
          </nav>
          <nav aria-label="...">
            <ul class="pagination m-0 mt-5">
              <li class="page-item">
                <a href="#" class="page-link anatomy-display-static" data-anatomy-colors="false" data-anatomy-popover="false">1</a>
              </li>
            </ul>
          </nav>
        </div>
      </td>
    </tr>
    <tr>
      <th scope="row">Large</th>
      <td class="anatomy-cell">
        <nav aria-label="..." style="width: 400px">
          <ul class="pagination pagination-lg anatomy-display-static" data-anatomy-colors="false" style="font-size: 16px">
            <li class="page-item">
              <a class="page-link" href="#">
                <i class="modus-icons">chevron_left</i>
              </a>
            </li>
            <li class="page-item">
              <a class="page-link" href="#">
                <i class="modus-icons">more_horizontal</i>
              </a>
            </li>
            <li class="page-item">
              <a class="page-link" href="#"> 3 </a>
            </li>
            <li class="page-item">
              <a class="page-link" href="#"> 4 </a>
            </li>
            <li class="page-item">
              <a class="page-link" href="#">
                <i class="modus-icons">more_horizontal</i>
              </a>
            </li>
            <li class="page-item">
              <a class="page-link" href="#">
                <i class="modus-icons">chevron_right</i>
              </a>
            </li>
          </ul>
        </nav>
        <nav aria-label="...">
          <ul class="pagination pagination-lg m-0 mt-5">
            <li class="page-item">
              <a href="#" class="page-link anatomy-display-static" data-anatomy-colors="false" data-anatomy-popover="false">1</a>
            </li>
          </ul>
        </nav>
      </td>
    </tr>
  </tbody>
</table>

<br>

- Use no arrows when number of pages is eight or fewer.
- Display a maximum interval of eight pages at a time.
- Single caret icon increments by one page.
- Double caret icon jumps to the first or last page.
- Distinctive highlight for current page.

### Behaviors

- Disable the first and previous arrow icons (and their labels) when the first page is selected.

<div class="guide-example-block">
  <div class="guide-sample">
    <nav aria-label="...">
      <ul class="pagination m-0">
        <li class="page-item disabled">
          <a class="page-link" href="#">
            <i class="modus-icons">chevron_left</i>
          </a>
        </li>
        <li class="page-item disabled">
          <a class="page-link" href="#">
            <i class="modus-icons">more_horizontal</i>
          </a>
        </li>
        <li class="page-item">
          <a class="page-link" href="#">
            3
          </a>
        </li>
        <li class="page-item">
          <a class="page-link" href="#">
            4
          </a>
        </li>
        <li class="page-item active" aria-current="page">
          <a class="page-link" href="#"
            >5 <span class="sr-only">(current)</span></a
          >
        </li>
        <li class="page-item">
          <a class="page-link" href="#">
            6
          </a>
        </li>
        <li class="page-item">
          <a class="page-link" href="#">
            7
          </a>
        </li>
        <li class="page-item">
          <a class="page-link" href="#">
            <i class="modus-icons">more_horizontal</i>
          </a>
        </li>
        <li class="page-item">
          <a class="page-link" href="#">
            <i class="modus-icons">chevron_right</i>
          </a>
        </li>
      </ul>
    </nav>
  </div>
</div>

<br>

- Disable the next and last arrow icons (and their labels) when the last page is selected.

<div class="guide-example-block">
  <div class="guide-sample">
    <nav aria-label="...">
      <ul class="pagination m-0">
        <li class="page-item">
          <a class="page-link" href="#">
            <i class="modus-icons">chevron_left</i>
          </a>
        </li>
        <li class="page-item">
          <a class="page-link" href="#">
            <i class="modus-icons">more_horizontal</i>
          </a>
        </li>
        <li class="page-item">
          <a class="page-link" href="#">
            3
          </a>
        </li>
        <li class="page-item">
          <a class="page-link" href="#">
            4
          </a>
        </li>
        <li class="page-item active" aria-current="page">
          <a class="page-link" href="#"
            >5 <span class="sr-only">(current)</span></a
          >
        </li>
        <li class="page-item">
          <a class="page-link" href="#">
            6
          </a>
        </li>
        <li class="page-item">
          <a class="page-link" href="#">
            7
          </a>
        </li>
        <li class="page-item disabled">
          <a class="page-link" href="#">
            <i class="modus-icons">more_horizontal</i>
          </a>
        </li>
        <li class="page-item disabled">
          <a class="page-link" href="#">
            <i class="modus-icons">chevron_right</i>
          </a>
        </li>
      </ul>
    </nav>
  </div>
</div>

### Accessibility

- Use a wrapping `<nav>` element to identify it as a navigation section to screen readers and other assistive technologies.
- Pagination is built with the ordered list `ol` HTML elements, so screen readers can announce the number of available links.
