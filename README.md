## Hi there 👋

<!--
**campsoftware/campsoftware** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<div class="js-pinned-items-reorder-container">
    <div class="float-right">
      <button id="dialog-show-dialog-ece11fc0-884f-4689-b504-a13a6021cde5" data-show-dialog-id="dialog-ece11fc0-884f-4689-b504-a13a6021cde5" type="button" data-view-component="true" class="pinned-items-setting-link Button--link Button--medium Button">  <span class="Button-content">
    <span class="Button-label">Customize your pins</span>
  </span>
</button>

<dialog-helper>
  <dialog data-hydro-click="{&quot;event_type&quot;:&quot;user_profile.click&quot;,&quot;payload&quot;:{&quot;profile_user_id&quot;:160516,&quot;target&quot;:&quot;CUSTOMIZE_PINS_LINK&quot;,&quot;user_id&quot;:160516,&quot;originating_url&quot;:&quot;https://github.com/campsoftware&quot;}}" data-hydro-click-hmac="540dd87d0b9b5dcaf78955f1e60226ed4c738375f45b74cb5473fa44475911da" data-test-selector="customize-your-pins" id="dialog-ece11fc0-884f-4689-b504-a13a6021cde5" aria-modal="true" aria-labelledby="dialog-ece11fc0-884f-4689-b504-a13a6021cde5-title" aria-describedby="dialog-ece11fc0-884f-4689-b504-a13a6021cde5-description" data-view-component="true" class="Overlay Overlay-whenNarrow Overlay--size-medium-portrait Overlay--motion-scaleFade Overlay--disableScroll">
    <div data-view-component="true" class="Overlay-header">
  <div class="Overlay-headerContentWrap">
    <div class="Overlay-titleWrap">
      <h1 class="Overlay-title " id="dialog-ece11fc0-884f-4689-b504-a13a6021cde5-title">
        Edit pinned items
      </h1>
        
    </div>
    <div class="Overlay-actionWrap">
      <button data-close-dialog-id="dialog-ece11fc0-884f-4689-b504-a13a6021cde5" aria-label="Close" type="button" data-view-component="true" class="close-button Overlay-closeButton"><svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x">
    <path d="M3.72 3.72a.75.75 0 0 1 1.06 0L8 6.94l3.22-3.22a.749.749 0 0 1 1.275.326.749.749 0 0 1-.215.734L9.06 8l3.22 3.22a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L8 9.06l-3.22 3.22a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L6.94 8 3.72 4.78a.75.75 0 0 1 0-1.06Z"></path>
</svg></button>
    </div>
  </div>
  
</div>
      <scrollable-region data-labelled-by="dialog-ece11fc0-884f-4689-b504-a13a6021cde5-title" data-catalyst="" style="overflow: auto;">
        <div data-view-component="true" class="Overlay-body">    
<profile-pins class="f5 d-flex flex-column overflow-hidden height-full" max="6" data-catalyst="">
  <div class="tmp-mb-3">
    <p class="color-fg-muted">
      Select up to six public repositories or gists you'd like to show to anyone.
    </p>
    <filter-input aria-owns="pinnable-items" data-target="profile-pins.filterInput" data-action="filter-input-start:profile-pins#setFilteringLogic" data-aria-live-element="profile-pin-dialog-live">
      <div class="d-flex flex-column flex-lg-row flex-auto">
        <div class="auto-search-group mb-1 mb-lg-0 mr-lg-1 flex-auto">
          <input type="search" aria-label="Filter repositories and gists" class="form-control width-full auto-search-input" data-target="profile-pins.input" data-action="focus:profile-pins#loadMorePinnableItems" placeholder="Filter repositories and gists" autocomplete="off" spellcheck="false">
          <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-search">
    <path d="M10.68 11.74a6 6 0 0 1-7.922-8.982 6 6 0 0 1 8.982 7.922l3.04 3.04a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215ZM11.5 7a4.499 4.499 0 1 0-8.997 0A4.499 4.499 0 0 0 11.5 7Z"></path>
</svg>
        </div>
      </div>
    </filter-input>
      <div class="tmp-mt-3 d-flex flex-items-center">
        <span class="text-bold">Show:</span>
        <div class="form-checkbox tmp-ml-4 my-0">
          <label class="text-normal">
            <input type="checkbox" value="repository" data-action="change:profile-pins#disableLastCheckedInput change:profile-pins#filter" data-targets="profile-pins.filterTypeInputs" checked="">
            Repositories
          </label>
        </div>
        <div class="form-checkbox tmp-ml-4 my-0">
          <label class="text-normal">
            <input type="checkbox" value="gist" data-action="change:profile-pins#disableLastCheckedInput change:profile-pins#filter" data-targets="profile-pins.filterTypeInputs" checked="">
            Gists
          </label>
        </div>
      </div>
    <div class="flex-self-center text-small lh-condensed-ultra mt-2 color-fg-muted " data-remaining-label="remaining" data-target="profile-pins.limitNotice">
      6 remaining
    </div>
  </div>

  <remote-pagination class="pt-2 overflow-auto border-top" data-target="profile-pins.remotePagination" data-action="remote-pagination-load:profile-pins#filter remote-pagination-load:profile-pins#limitPins" id="pinnable-items" data-catalyst="">
    <!-- '"` --><!-- </textarea></xmp> --><form id="pinned-items-update-form" data-target="profile-pins.form" data-action="change:profile-pins#limitPins reset:profile-pins#limitPins" data-turbo="false" action="/users/campsoftware/set_pinned_items" accept-charset="UTF-8" method="post"><input type="hidden" name="_method" value="put" autocomplete="off"><input type="hidden" name="authenticity_token" value="-sgQju_vfMtAKtH0-c5x3W94j7pkzTN8yXukYsO2M7kbCskbuNQcdlE2dBAmFkPnRIrS2zqGS0xo7Eaej1U5NQ">
      <input type="hidden" name="view_as" value="">
      <ul data-filter-list="" class="list-style-none position-relative" data-target="remote-pagination.list">
          <li class="source no-description" data-pinnable-type="repository" data-pagination-src="">
  <input type="checkbox" name="pinned_items_id_and_type[]" value="1174661885-Repository" id="pinned-item-1174661885-Repository-user-profile" class="f5 pinned-item-checkbox m-2 position-absolute" data-targets="profile-pins.checkboxes" data-action="change:profile-pins#formModified">
  <label class="pinned-item-name d-flex flex-items-start tmp-pl-5 p-1" for="pinned-item-1174661885-Repository-user-profile">
    <svg aria-label="public repo" role="img" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-repo flex-shrink-0 mt-1 mr-2">
    <path d="M2 2.5A2.5 2.5 0 0 1 4.5 0h8.75a.75.75 0 0 1 .75.75v12.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1 0-1.5h1.75v-2h-8a1 1 0 0 0-.714 1.7.75.75 0 1 1-1.072 1.05A2.495 2.495 0 0 1 2 11.5Zm10.5-1h-8a1 1 0 0 0-1 1v6.708A2.486 2.486 0 0 1 4.5 9h8ZM5 12.25a.25.25 0 0 1 .25-.25h3.5a.25.25 0 0 1 .25.25v3.25a.25.25 0 0 1-.4.2l-1.45-1.087a.249.249 0 0 0-.3 0L5.4 15.7a.25.25 0 0 1-.4-.2Z"></path>
</svg>
    <strong class="width-fit flex-auto wb-break-word" data-filter-item-text="">
      campsoftware
    </strong>
    <span class="stars no-wrap color-fg-muted">
      0
      <svg aria-label="stars" role="img" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-star">
    <path d="M8 .25a.75.75 0 0 1 .673.418l1.882 3.815 4.21.612a.75.75 0 0 1 .416 1.279l-3.046 2.97.719 4.192a.751.751 0 0 1-1.088.791L8 12.347l-3.766 1.98a.75.75 0 0 1-1.088-.79l.72-4.194L.818 6.374a.75.75 0 0 1 .416-1.28l4.21-.611L7.327.668A.75.75 0 0 1 8 .25Zm0 2.445L6.615 5.5a.75.75 0 0 1-.564.41l-3.097.45 2.24 2.184a.75.75 0 0 1 .216.664l-.528 3.084 2.769-1.456a.75.75 0 0 1 .698 0l2.77 1.456-.53-3.084a.75.75 0 0 1 .216-.664l2.24-2.183-3.096-.45a.75.75 0 0 1-.564-.41L8 2.694Z"></path>
</svg>
    </span>
  </label>
</li>

  <li class="source" data-pinnable-type="repository" data-pagination-src="">
  <input type="checkbox" name="pinned_items_id_and_type[]" value="487400278-Repository" id="pinned-item-487400278-Repository-user-profile" class="f5 pinned-item-checkbox m-2 position-absolute" data-targets="profile-pins.checkboxes" data-action="change:profile-pins#formModified">
  <label class="pinned-item-name d-flex flex-items-start tmp-pl-5 p-1" for="pinned-item-487400278-Repository-user-profile">
    <svg aria-label="public repo" role="img" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-repo flex-shrink-0 mt-1 mr-2">
    <path d="M2 2.5A2.5 2.5 0 0 1 4.5 0h8.75a.75.75 0 0 1 .75.75v12.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1 0-1.5h1.75v-2h-8a1 1 0 0 0-.714 1.7.75.75 0 1 1-1.072 1.05A2.495 2.495 0 0 1 2 11.5Zm10.5-1h-8a1 1 0 0 0-1 1v6.708A2.486 2.486 0 0 1 4.5 9h8ZM5 12.25a.25.25 0 0 1 .25-.25h3.5a.25.25 0 0 1 .25.25v3.25a.25.25 0 0 1-.4.2l-1.45-1.087a.249.249 0 0 0-.3 0L5.4 15.7a.25.25 0 0 1-.4-.2Z"></path>
</svg>
    <strong class="width-fit flex-auto wb-break-word" data-filter-item-text="">
      css-namedColors
    </strong>
    <span class="stars no-wrap color-fg-muted">
      0
      <svg aria-label="stars" role="img" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-star">
    <path d="M8 .25a.75.75 0 0 1 .673.418l1.882 3.815 4.21.612a.75.75 0 0 1 .416 1.279l-3.046 2.97.719 4.192a.751.751 0 0 1-1.088.791L8 12.347l-3.766 1.98a.75.75 0 0 1-1.088-.79l.72-4.194L.818 6.374a.75.75 0 0 1 .416-1.28l4.21-.611L7.327.668A.75.75 0 0 1 8 .25Zm0 2.445L6.615 5.5a.75.75 0 0 1-.564.41l-3.097.45 2.24 2.184a.75.75 0 0 1 .216.664l-.528 3.084 2.769-1.456a.75.75 0 0 1 .698 0l2.77 1.456-.53-3.084a.75.75 0 0 1 .216-.664l2.24-2.183-3.096-.45a.75.75 0 0 1-.564-.41L8 2.694Z"></path>
</svg>
    </span>
  </label>
</li>

  <li class="source" data-pinnable-type="repository" data-pagination-src="">
  <input type="checkbox" name="pinned_items_id_and_type[]" value="287021078-Repository" id="pinned-item-287021078-Repository-user-profile" class="f5 pinned-item-checkbox m-2 position-absolute" data-targets="profile-pins.checkboxes" data-action="change:profile-pins#formModified">
  <label class="pinned-item-name d-flex flex-items-start tmp-pl-5 p-1" for="pinned-item-287021078-Repository-user-profile">
    <svg aria-label="public repo" role="img" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-repo flex-shrink-0 mt-1 mr-2">
    <path d="M2 2.5A2.5 2.5 0 0 1 4.5 0h8.75a.75.75 0 0 1 .75.75v12.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1 0-1.5h1.75v-2h-8a1 1 0 0 0-.714 1.7.75.75 0 1 1-1.072 1.05A2.495 2.495 0 0 1 2 11.5Zm10.5-1h-8a1 1 0 0 0-1 1v6.708A2.486 2.486 0 0 1 4.5 9h8ZM5 12.25a.25.25 0 0 1 .25-.25h3.5a.25.25 0 0 1 .25.25v3.25a.25.25 0 0 1-.4.2l-1.45-1.087a.249.249 0 0 0-.3 0L5.4 15.7a.25.25 0 0 1-.4-.2Z"></path>
</svg>
    <strong class="width-fit flex-auto wb-break-word" data-filter-item-text="">
      js-locationGet
    </strong>
    <span class="stars no-wrap color-fg-muted">
      0
      <svg aria-label="stars" role="img" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-star">
    <path d="M8 .25a.75.75 0 0 1 .673.418l1.882 3.815 4.21.612a.75.75 0 0 1 .416 1.279l-3.046 2.97.719 4.192a.751.751 0 0 1-1.088.791L8 12.347l-3.766 1.98a.75.75 0 0 1-1.088-.79l.72-4.194L.818 6.374a.75.75 0 0 1 .416-1.28l4.21-.611L7.327.668A.75.75 0 0 1 8 .25Zm0 2.445L6.615 5.5a.75.75 0 0 1-.564.41l-3.097.45 2.24 2.184a.75.75 0 0 1 .216.664l-.528 3.084 2.769-1.456a.75.75 0 0 1 .698 0l2.77 1.456-.53-3.084a.75.75 0 0 1 .216-.664l2.24-2.183-3.096-.45a.75.75 0 0 1-.564-.41L8 2.694Z"></path>
</svg>
    </span>
  </label>
</li>

  <li class="source" data-pinnable-type="repository" data-pagination-src="">
  <input type="checkbox" name="pinned_items_id_and_type[]" value="988572294-Repository" id="pinned-item-988572294-Repository-user-profile" class="f5 pinned-item-checkbox m-2 position-absolute" data-targets="profile-pins.checkboxes" data-action="change:profile-pins#formModified">
  <label class="pinned-item-name d-flex flex-items-start tmp-pl-5 p-1" for="pinned-item-988572294-Repository-user-profile">
    <svg aria-label="public repo" role="img" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-repo flex-shrink-0 mt-1 mr-2">
    <path d="M2 2.5A2.5 2.5 0 0 1 4.5 0h8.75a.75.75 0 0 1 .75.75v12.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1 0-1.5h1.75v-2h-8a1 1 0 0 0-.714 1.7.75.75 0 1 1-1.072 1.05A2.495 2.495 0 0 1 2 11.5Zm10.5-1h-8a1 1 0 0 0-1 1v6.708A2.486 2.486 0 0 1 4.5 9h8ZM5 12.25a.25.25 0 0 1 .25-.25h3.5a.25.25 0 0 1 .25.25v3.25a.25.25 0 0 1-.4.2l-1.45-1.087a.249.249 0 0 0-.3 0L5.4 15.7a.25.25 0 0 1-.4-.2Z"></path>
</svg>
    <strong class="width-fit flex-auto wb-break-word" data-filter-item-text="">
      js-navTimingAPI
    </strong>
    <span class="stars no-wrap color-fg-muted">
      0
      <svg aria-label="stars" role="img" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-star">
    <path d="M8 .25a.75.75 0 0 1 .673.418l1.882 3.815 4.21.612a.75.75 0 0 1 .416 1.279l-3.046 2.97.719 4.192a.751.751 0 0 1-1.088.791L8 12.347l-3.766 1.98a.75.75 0 0 1-1.088-.79l.72-4.194L.818 6.374a.75.75 0 0 1 .416-1.28l4.21-.611L7.327.668A.75.75 0 0 1 8 .25Zm0 2.445L6.615 5.5a.75.75 0 0 1-.564.41l-3.097.45 2.24 2.184a.75.75 0 0 1 .216.664l-.528 3.084 2.769-1.456a.75.75 0 0 1 .698 0l2.77 1.456-.53-3.084a.75.75 0 0 1 .216-.664l2.24-2.183-3.096-.45a.75.75 0 0 1-.564-.41L8 2.694Z"></path>
</svg>
    </span>
  </label>
</li>

  <li class="source" data-pinnable-type="repository" data-pagination-src="">
  <input type="checkbox" name="pinned_items_id_and_type[]" value="858970104-Repository" id="pinned-item-858970104-Repository-user-profile" class="f5 pinned-item-checkbox m-2 position-absolute" data-targets="profile-pins.checkboxes" data-action="change:profile-pins#formModified">
  <label class="pinned-item-name d-flex flex-items-start tmp-pl-5 p-1" for="pinned-item-858970104-Repository-user-profile">
    <svg aria-label="public repo" role="img" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-repo flex-shrink-0 mt-1 mr-2">
    <path d="M2 2.5A2.5 2.5 0 0 1 4.5 0h8.75a.75.75 0 0 1 .75.75v12.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1 0-1.5h1.75v-2h-8a1 1 0 0 0-.714 1.7.75.75 0 1 1-1.072 1.05A2.495 2.495 0 0 1 2 11.5Zm10.5-1h-8a1 1 0 0 0-1 1v6.708A2.486 2.486 0 0 1 4.5 9h8ZM5 12.25a.25.25 0 0 1 .25-.25h3.5a.25.25 0 0 1 .25.25v3.25a.25.25 0 0 1-.4.2l-1.45-1.087a.249.249 0 0 0-.3 0L5.4 15.7a.25.25 0 0 1-.4-.2Z"></path>
</svg>
    <strong class="width-fit flex-auto wb-break-word" data-filter-item-text="">
      php-backTrace
    </strong>
    <span class="stars no-wrap color-fg-muted">
      0
      <svg aria-label="stars" role="img" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-star">
    <path d="M8 .25a.75.75 0 0 1 .673.418l1.882 3.815 4.21.612a.75.75 0 0 1 .416 1.279l-3.046 2.97.719 4.192a.751.751 0 0 1-1.088.791L8 12.347l-3.766 1.98a.75.75 0 0 1-1.088-.79l.72-4.194L.818 6.374a.75.75 0 0 1 .416-1.28l4.21-.611L7.327.668A.75.75 0 0 1 8 .25Zm0 2.445L6.615 5.5a.75.75 0 0 1-.564.41l-3.097.45 2.24 2.184a.75.75 0 0 1 .216.664l-.528 3.084 2.769-1.456a.75.75 0 0 1 .698 0l2.77 1.456-.53-3.084a.75.75 0 0 1 .216-.664l2.24-2.183-3.096-.45a.75.75 0 0 1-.564-.41L8 2.694Z"></path>
</svg>
    </span>
  </label>
</li>

  <li class="source" data-pinnable-type="repository" data-pagination-src="">
  <input type="checkbox" name="pinned_items_id_and_type[]" value="1174650690-Repository" id="pinned-item-1174650690-Repository-user-profile" class="f5 pinned-item-checkbox m-2 position-absolute" data-targets="profile-pins.checkboxes" data-action="change:profile-pins#formModified">
  <label class="pinned-item-name d-flex flex-items-start tmp-pl-5 p-1" for="pinned-item-1174650690-Repository-user-profile">
    <svg aria-label="public repo" role="img" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-repo flex-shrink-0 mt-1 mr-2">
    <path d="M2 2.5A2.5 2.5 0 0 1 4.5 0h8.75a.75.75 0 0 1 .75.75v12.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1 0-1.5h1.75v-2h-8a1 1 0 0 0-.714 1.7.75.75 0 1 1-1.072 1.05A2.495 2.495 0 0 1 2 11.5Zm10.5-1h-8a1 1 0 0 0-1 1v6.708A2.486 2.486 0 0 1 4.5 9h8ZM5 12.25a.25.25 0 0 1 .25-.25h3.5a.25.25 0 0 1 .25.25v3.25a.25.25 0 0 1-.4.2l-1.45-1.087a.249.249 0 0 0-.3 0L5.4 15.7a.25.25 0 0 1-.4-.2Z"></path>
</svg>
    <strong class="width-fit flex-auto wb-break-word" data-filter-item-text="">
      php-chart.js
    </strong>
    <span class="stars no-wrap color-fg-muted">
      0
      <svg aria-label="stars" role="img" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-star">
    <path d="M8 .25a.75.75 0 0 1 .673.418l1.882 3.815 4.21.612a.75.75 0 0 1 .416 1.279l-3.046 2.97.719 4.192a.751.751 0 0 1-1.088.791L8 12.347l-3.766 1.98a.75.75 0 0 1-1.088-.79l.72-4.194L.818 6.374a.75.75 0 0 1 .416-1.28l4.21-.611L7.327.668A.75.75 0 0 1 8 .25Zm0 2.445L6.615 5.5a.75.75 0 0 1-.564.41l-3.097.45 2.24 2.184a.75.75 0 0 1 .216.664l-.528 3.084 2.769-1.456a.75.75 0 0 1 .698 0l2.77 1.456-.53-3.084a.75.75 0 0 1 .216-.664l2.24-2.183-3.096-.45a.75.75 0 0 1-.564-.41L8 2.694Z"></path>
</svg>
    </span>
  </label>
</li>

  <li class="source" data-pinnable-type="repository" data-pagination-src="">
  <input type="checkbox" name="pinned_items_id_and_type[]" value="287122327-Repository" id="pinned-item-287122327-Repository-user-profile" class="f5 pinned-item-checkbox m-2 position-absolute" data-targets="profile-pins.checkboxes" data-action="change:profile-pins#formModified">
  <label class="pinned-item-name d-flex flex-items-start tmp-pl-5 p-1" for="pinned-item-287122327-Repository-user-profile">
    <svg aria-label="public repo" role="img" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-repo flex-shrink-0 mt-1 mr-2">
    <path d="M2 2.5A2.5 2.5 0 0 1 4.5 0h8.75a.75.75 0 0 1 .75.75v12.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1 0-1.5h1.75v-2h-8a1 1 0 0 0-.714 1.7.75.75 0 1 1-1.072 1.05A2.495 2.495 0 0 1 2 11.5Zm10.5-1h-8a1 1 0 0 0-1 1v6.708A2.486 2.486 0 0 1 4.5 9h8ZM5 12.25a.25.25 0 0 1 .25-.25h3.5a.25.25 0 0 1 .25.25v3.25a.25.25 0 0 1-.4.2l-1.45-1.087a.249.249 0 0 0-.3 0L5.4 15.7a.25.25 0 0 1-.4-.2Z"></path>
</svg>
    <strong class="width-fit flex-auto wb-break-word" data-filter-item-text="">
      php-semaphoreCheck
    </strong>
    <span class="stars no-wrap color-fg-muted">
      0
      <svg aria-label="stars" role="img" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-star">
    <path d="M8 .25a.75.75 0 0 1 .673.418l1.882 3.815 4.21.612a.75.75 0 0 1 .416 1.279l-3.046 2.97.719 4.192a.751.751 0 0 1-1.088.791L8 12.347l-3.766 1.98a.75.75 0 0 1-1.088-.79l.72-4.194L.818 6.374a.75.75 0 0 1 .416-1.28l4.21-.611L7.327.668A.75.75 0 0 1 8 .25Zm0 2.445L6.615 5.5a.75.75 0 0 1-.564.41l-3.097.45 2.24 2.184a.75.75 0 0 1 .216.664l-.528 3.084 2.769-1.456a.75.75 0 0 1 .698 0l2.77 1.456-.53-3.084a.75.75 0 0 1 .216-.664l2.24-2.183-3.096-.45a.75.75 0 0 1-.564-.41L8 2.694Z"></path>
</svg>
    </span>
  </label>
</li>

  <li class="source" data-pinnable-type="repository" data-pagination-src="">
  <input type="checkbox" name="pinned_items_id_and_type[]" value="1003911098-Repository" id="pinned-item-1003911098-Repository-user-profile" class="f5 pinned-item-checkbox m-2 position-absolute" data-targets="profile-pins.checkboxes" data-action="change:profile-pins#formModified">
  <label class="pinned-item-name d-flex flex-items-start tmp-pl-5 p-1" for="pinned-item-1003911098-Repository-user-profile">
    <svg aria-label="public repo" role="img" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-repo flex-shrink-0 mt-1 mr-2">
    <path d="M2 2.5A2.5 2.5 0 0 1 4.5 0h8.75a.75.75 0 0 1 .75.75v12.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1 0-1.5h1.75v-2h-8a1 1 0 0 0-.714 1.7.75.75 0 1 1-1.072 1.05A2.495 2.495 0 0 1 2 11.5Zm10.5-1h-8a1 1 0 0 0-1 1v6.708A2.486 2.486 0 0 1 4.5 9h8ZM5 12.25a.25.25 0 0 1 .25-.25h3.5a.25.25 0 0 1 .25.25v3.25a.25.25 0 0 1-.4.2l-1.45-1.087a.249.249 0 0 0-.3 0L5.4 15.7a.25.25 0 0 1-.4-.2Z"></path>
</svg>
    <strong class="width-fit flex-auto wb-break-word" data-filter-item-text="">
      Xanadu-ChangeLog
    </strong>
    <span class="stars no-wrap color-fg-muted">
      0
      <svg aria-label="stars" role="img" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-star">
    <path d="M8 .25a.75.75 0 0 1 .673.418l1.882 3.815 4.21.612a.75.75 0 0 1 .416 1.279l-3.046 2.97.719 4.192a.751.751 0 0 1-1.088.791L8 12.347l-3.766 1.98a.75.75 0 0 1-1.088-.79l.72-4.194L.818 6.374a.75.75 0 0 1 .416-1.28l4.21-.611L7.327.668A.75.75 0 0 1 8 .25Zm0 2.445L6.615 5.5a.75.75 0 0 1-.564.41l-3.097.45 2.24 2.184a.75.75 0 0 1 .216.664l-.528 3.084 2.769-1.456a.75.75 0 0 1 .698 0l2.77 1.456-.53-3.084a.75.75 0 0 1 .216-.664l2.24-2.183-3.096-.45a.75.75 0 0 1-.564-.41L8 2.694Z"></path>
</svg>
    </span>
  </label>
</li>

  <li class="source no-description" data-pinnable-type="gist" data-pagination-src="">
  <input type="checkbox" name="pinned_items_id_and_type[]" value="30940568-Gist" id="pinned-item-30940568-Gist-user-profile" class="f5 pinned-item-checkbox m-2 position-absolute" data-targets="profile-pins.checkboxes" data-action="change:profile-pins#formModified">
  <label class="pinned-item-name d-flex flex-items-start tmp-pl-5 p-1" for="pinned-item-30940568-Gist-user-profile">
    <svg aria-label="gist" role="img" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-code-square flex-shrink-0 mt-1 mr-2">
    <path d="M0 1.75C0 .784.784 0 1.75 0h12.5C15.216 0 16 .784 16 1.75v12.5A1.75 1.75 0 0 1 14.25 16H1.75A1.75 1.75 0 0 1 0 14.25Zm1.75-.25a.25.25 0 0 0-.25.25v12.5c0 .138.112.25.25.25h12.5a.25.25 0 0 0 .25-.25V1.75a.25.25 0 0 0-.25-.25Zm7.47 3.97a.75.75 0 0 1 1.06 0l2 2a.75.75 0 0 1 0 1.06l-2 2a.749.749 0 0 1-1.275-.326.749.749 0 0 1 .215-.734L10.69 8 9.22 6.53a.75.75 0 0 1 0-1.06ZM6.78 6.53 5.31 8l1.47 1.47a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215l-2-2a.75.75 0 0 1 0-1.06l2-2a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042Z"></path>
</svg>
    <strong class="width-fit flex-auto wb-break-word" data-filter-item-text="">
      keybase.md
    </strong>
    <span class="stars no-wrap color-fg-muted">
      0
      <svg aria-label="stars" role="img" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-star">
    <path d="M8 .25a.75.75 0 0 1 .673.418l1.882 3.815 4.21.612a.75.75 0 0 1 .416 1.279l-3.046 2.97.719 4.192a.751.751 0 0 1-1.088.791L8 12.347l-3.766 1.98a.75.75 0 0 1-1.088-.79l.72-4.194L.818 6.374a.75.75 0 0 1 .416-1.28l4.21-.611L7.327.668A.75.75 0 0 1 8 .25Zm0 2.445L6.615 5.5a.75.75 0 0 1-.564.41l-3.097.45 2.24 2.184a.75.75 0 0 1 .216.664l-.528 3.084 2.769-1.456a.75.75 0 0 1 .698 0l2.77 1.456-.53-3.084a.75.75 0 0 1 .216-.664l2.24-2.183-3.096-.45a.75.75 0 0 1-.564-.41L8 2.694Z"></path>
</svg>
    </span>
  </label>
</li>

  <li class="source" data-pinnable-type="repository" data-pagination-src="">
  <input type="checkbox" name="pinned_items_id_and_type[]" value="103784142-Repository" id="pinned-item-103784142-Repository-user-profile" class="f5 pinned-item-checkbox m-2 position-absolute" data-targets="profile-pins.checkboxes" data-action="change:profile-pins#formModified">
  <label class="pinned-item-name d-flex flex-items-start tmp-pl-5 p-1" for="pinned-item-103784142-Repository-user-profile">
    <svg aria-label="public repo" role="img" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-repo flex-shrink-0 mt-1 mr-2">
    <path d="M2 2.5A2.5 2.5 0 0 1 4.5 0h8.75a.75.75 0 0 1 .75.75v12.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1 0-1.5h1.75v-2h-8a1 1 0 0 0-.714 1.7.75.75 0 1 1-1.072 1.05A2.495 2.495 0 0 1 2 11.5Zm10.5-1h-8a1 1 0 0 0-1 1v6.708A2.486 2.486 0 0 1 4.5 9h8ZM5 12.25a.25.25 0 0 1 .25-.25h3.5a.25.25 0 0 1 .25.25v3.25a.25.25 0 0 1-.4.2l-1.45-1.087a.249.249 0 0 0-.3 0L5.4 15.7a.25.25 0 0 1-.4-.2Z"></path>
</svg>
    <strong class="width-fit flex-auto wb-break-word" data-filter-item-text="">
      MonitorControl/MonitorControl
    </strong>
    <span class="stars no-wrap color-fg-muted">
      32.6k
      <svg aria-label="stars" role="img" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-star">
    <path d="M8 .25a.75.75 0 0 1 .673.418l1.882 3.815 4.21.612a.75.75 0 0 1 .416 1.279l-3.046 2.97.719 4.192a.751.751 0 0 1-1.088.791L8 12.347l-3.766 1.98a.75.75 0 0 1-1.088-.79l.72-4.194L.818 6.374a.75.75 0 0 1 .416-1.28l4.21-.611L7.327.668A.75.75 0 0 1 8 .25Zm0 2.445L6.615 5.5a.75.75 0 0 1-.564.41l-3.097.45 2.24 2.184a.75.75 0 0 1 .216.664l-.528 3.084 2.769-1.456a.75.75 0 0 1 .698 0l2.77 1.456-.53-3.084a.75.75 0 0 1 .216-.664l2.24-2.183-3.096-.45a.75.75 0 0 1-.564-.41L8 2.694Z"></path>
</svg>
    </span>
  </label>
</li>


      </ul>
      <div class="color-fg-muted m-1" data-filter-empty-state="" hidden="">
        No repositories or gists found.
      </div>
</form>    <!-- '"` --><!-- </textarea></xmp> --><form class="tmp-mb-3" hidden="" data-target="remote-pagination.form" data-action="submit:remote-pagination#submit" data-turbo="false" action="" accept-charset="UTF-8" method="get">
      <button data-target="remote-pagination.submitButton" type="submit" data-view-component="true" class="Button--link Button--medium Button">  <span class="Button-content">
    <span class="Button-label">Load more</span>
  </span>
</button>

</form>  </remote-pagination>

  <div id="profile-pin-dialog-live" class="sr-only" aria-live="polite" aria-atomic="true"></div>
</profile-pins>
</div>
      </scrollable-region>
      <div data-view-component="true" class="Overlay-footer Overlay-footer--alignEnd Overlay-footer--divided">    <button form="pinned-items-update-form" type="submit" disabled="disabled" data-view-component="true" class="js-pinned-items-submit Button--primary Button--medium Button">  <span class="Button-content">
    <span class="Button-label">Save pins</span>
  </span>
</button>
</div>
</dialog></dialog-helper>

    </div>
  <h2 class="f4 mb-2 text-normal">
      Popular repositories
    <span data-view-component="true">
  <svg style="box-sizing: content-box; color: var(--color-icon-primary);" width="16" height="16" viewBox="0 0 16 16" fill="none" aria-hidden="true" data-view-component="true" class="spinner pinned-items-spinner js-pinned-items-spinner v-align-text-bottom ml-1 anim-rotate">
    <circle cx="8" cy="8" r="7" stroke="currentColor" stroke-opacity="0.25" stroke-width="2" vector-effect="non-scaling-stroke" fill="none"></circle>
    <path d="M15 8a7.002 7.002 0 00-7-7" stroke="currentColor" stroke-width="2" stroke-linecap="round" vector-effect="non-scaling-stroke"></path>
</svg>    <span class="sr-only">Loading</span>
</span>
    <span class="ml-2 color-fg-muted f6 js-pinned-items-reorder-message" role="status" aria-live="polite" data-error-text="Something went wrong." data-success-text="Order updated."></span>
  </h2>

    <ol class="d-flex flex-wrap list-style-none gutter-condensed tmp-mb-4">

    <li class="tmp-mb-3 d-flex flex-content-stretch col-12 col-md-6 col-lg-6">
      <div class="Box pinned-item-list-item d-flex tmp-p-3 width-full public source">
        <div class="pinned-item-list-item-content">
          <div class="d-flex v-align-middle mr-2">
            <span data-view-component="true" class="position-relative"><a id="287021078" href="/campsoftware/js-locationGet" data-view-component="true" class="min-width-0 Link text-bold flex-auto wb-break-all" aria-describedby="tooltip-cbbf3ba5-9d44-4c6a-9b46-00216989b7f6"><span class="repo">
                js-locationGet
              </span></a>  <tool-tip id="tooltip-cbbf3ba5-9d44-4c6a-9b46-00216989b7f6" for="287021078" popover="manual" data-direction="n" data-type="description" data-view-component="true" class="position-absolute sr-only" role="tooltip" style="--tool-tip-position-top: 312.5375175476074px; --tool-tip-position-left: 525.6909408569336px;">js-locationGet</tool-tip></span>            <span class="flex-auto text-right">
              <span></span><span class="Label Label--secondary v-align-middle ">Public</span>
            </span>
          </div>


          <p class="pinned-item-desc color-fg-muted text-small d-block mt-2 tmp-mb-3">
            Retrieves the GPS coordinates of the Browser with Javascript. Uses an inline callback. Normalizes the output.
          </p>

          <p class="mb-0 f6 color-fg-muted">
          </p>
        </div>
      </div>
    </li>

    <li class="tmp-mb-3 d-flex flex-content-stretch col-12 col-md-6 col-lg-6">
      <div class="Box pinned-item-list-item d-flex tmp-p-3 width-full public source">
        <div class="pinned-item-list-item-content">
          <div class="d-flex v-align-middle mr-2">
            <span data-view-component="true" class="position-relative"><a id="287122327" href="/campsoftware/php-semaphoreCheck" data-view-component="true" class="min-width-0 Link text-bold flex-auto wb-break-all" aria-describedby="tooltip-268503ce-a55d-4db2-92b5-44b2e05b626f"><span class="repo">
                php-semaphoreCheck
              </span></a>  <tool-tip id="tooltip-268503ce-a55d-4db2-92b5-44b2e05b626f" for="287122327" popover="manual" data-direction="n" data-type="description" data-view-component="true" class="sr-only position-absolute" role="tooltip">php-semaphoreCheck</tool-tip></span>            <span class="flex-auto text-right">
              <span></span><span class="Label Label--secondary v-align-middle ">Public</span>
            </span>
          </div>


          <p class="pinned-item-desc color-fg-muted text-small d-block mt-2 tmp-mb-3">
            Gets a semaphore and attempts to acquire to prevent code from running more than one time.
          </p>

          <p class="mb-0 f6 color-fg-muted">
          </p>
        </div>
      </div>
    </li>

    <li class="tmp-mb-3 d-flex flex-content-stretch col-12 col-md-6 col-lg-6">
      <div class="Box pinned-item-list-item d-flex tmp-p-3 width-full public source">
        <div class="pinned-item-list-item-content">
          <div class="d-flex v-align-middle mr-2">
            <span data-view-component="true" class="position-relative"><a id="487400278" href="/campsoftware/css-namedColors" data-view-component="true" class="min-width-0 Link text-bold flex-auto wb-break-all" aria-describedby="tooltip-53ccc6c4-db2c-4b06-9be9-ff627a617433"><span class="repo">
                css-namedColors
              </span></a>  <tool-tip id="tooltip-53ccc6c4-db2c-4b06-9be9-ff627a617433" for="487400278" popover="manual" data-direction="n" data-type="description" data-view-component="true" class="sr-only position-absolute" role="tooltip">css-namedColors</tool-tip></span>            <span class="flex-auto text-right">
              <span></span><span class="Label Label--secondary v-align-middle ">Public</span>
            </span>
          </div>


          <p class="pinned-item-desc color-fg-muted text-small d-block mt-2 tmp-mb-3">
            Sometimes you need more colors. Named Colors are a great solution.
          </p>

          <p class="mb-0 f6 color-fg-muted">
              <span class="tmp-mr-3 d-inline-block">
  <span class="repo-language-color" style="background-color: #663399"></span>
  <span itemprop="programmingLanguage">CSS</span>
</span>

          </p>
        </div>
      </div>
    </li>

    <li class="tmp-mb-3 d-flex flex-content-stretch col-12 col-md-6 col-lg-6">
      <div class="Box pinned-item-list-item d-flex tmp-p-3 width-full public source">
        <div class="pinned-item-list-item-content">
          <div class="d-flex v-align-middle mr-2">
            <span data-view-component="true" class="position-relative"><a id="858970104" href="/campsoftware/php-backTrace" data-view-component="true" class="min-width-0 Link text-bold flex-auto wb-break-all" aria-describedby="tooltip-d2ef8370-8946-43da-8c7b-6d59fcfc7a05"><span class="repo">
                php-backTrace
              </span></a>  <tool-tip id="tooltip-d2ef8370-8946-43da-8c7b-6d59fcfc7a05" for="858970104" popover="manual" data-direction="n" data-type="description" data-view-component="true" class="position-absolute sr-only" role="tooltip" style="--tool-tip-position-top: 442.4499931335449px; --tool-tip-position-left: 982.2969741821289px;">php-backTrace</tool-tip></span>            <span class="flex-auto text-right">
              <span></span><span class="Label Label--secondary v-align-middle ">Public</span>
            </span>
          </div>


          <p class="pinned-item-desc color-fg-muted text-small d-block mt-2 tmp-mb-3">
            Creates a BackTrace in PHP and returns a string.
          </p>

          <p class="mb-0 f6 color-fg-muted">
          </p>
        </div>
      </div>
    </li>

    <li class="tmp-mb-3 d-flex flex-content-stretch col-12 col-md-6 col-lg-6">
      <div class="Box pinned-item-list-item d-flex tmp-p-3 width-full public source">
        <div class="pinned-item-list-item-content">
          <div class="d-flex v-align-middle mr-2">
            <span data-view-component="true" class="position-relative"><a id="988572294" href="/campsoftware/js-navTimingAPI" data-view-component="true" class="min-width-0 Link text-bold flex-auto wb-break-all" aria-describedby="tooltip-2a261bb0-1cd8-4f41-901d-be16a22f9119"><span class="repo">
                js-navTimingAPI
              </span></a>  <tool-tip id="tooltip-2a261bb0-1cd8-4f41-901d-be16a22f9119" for="988572294" popover="manual" data-direction="n" data-type="description" data-view-component="true" class="sr-only position-absolute" role="tooltip">js-navTimingAPI</tool-tip></span>            <span class="flex-auto text-right">
              <span></span><span class="Label Label--secondary v-align-middle ">Public</span>
            </span>
          </div>


          <p class="pinned-item-desc color-fg-muted text-small d-block mt-2 tmp-mb-3">
            Logs to console.log detailed timing metrics related to the navigation and load of a web page.
          </p>

          <p class="mb-0 f6 color-fg-muted">
          </p>
        </div>
      </div>
    </li>

    <li class="tmp-mb-3 d-flex flex-content-stretch col-12 col-md-6 col-lg-6">
      <div class="Box pinned-item-list-item d-flex tmp-p-3 width-full public source">
        <div class="pinned-item-list-item-content">
          <div class="d-flex v-align-middle mr-2">
            <span data-view-component="true" class="position-relative"><a id="1003911098" href="/campsoftware/Xanadu-ChangeLog" data-view-component="true" class="min-width-0 Link text-bold flex-auto wb-break-all" aria-describedby="tooltip-730aa837-0d8b-42be-8cca-040058538d8b"><span class="repo">
                Xanadu-ChangeLog
              </span></a>  <tool-tip id="tooltip-730aa837-0d8b-42be-8cca-040058538d8b" for="1003911098" popover="manual" data-direction="n" data-type="description" data-view-component="true" class="position-absolute sr-only" role="tooltip" style="--tool-tip-position-top: 572.3624992370605px; --tool-tip-position-left: 984.5847625732422px;">Xanadu-ChangeLog</tool-tip></span>            <span class="flex-auto text-right">
              <span></span><span class="Label Label--secondary v-align-middle ">Public</span>
            </span>
          </div>


          <p class="pinned-item-desc color-fg-muted text-small d-block mt-2 tmp-mb-3">
            Xanadu is a platform for developing Database-Driven Web Apps that use NGINX, PHP, HTML, Bootstrap, CSS, Javascript, and MySQL.
          </p>

          <p class="mb-0 f6 color-fg-muted">
          </p>
        </div>
      </div>
    </li>
</ol>

</div>
