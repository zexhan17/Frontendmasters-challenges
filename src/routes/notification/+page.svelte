<div class="rounded p-5 md:w-[40rem] mx-auto bg-white space-y-3">
    <div class="mb-6 flex justify-between">
        <div class="flex">
            <h4 class="font-extrabold">Notifications</h4>
            <span class="count ml-2">3</span>
        </div>
        <span class="hover">Mark all as read</span>
    </div>
    <!-- 1 -->
    <div class="rounded-md p-3 unread flex items-start gap-2">
        <img
            class="cursor-pointer"
            height="50"
            width="50"
            src="notifi/6.webp"
            alt="avatar"
        />
        <div>
            <div>
                <span class="name">Mark Webber</span>
                <span>react to your recent post</span>
                <span class="hover f800 ml-1 dot">
                    My first tournament today!
                </span>
            </div>
            <!-- <span class="flex items-center flex-wrap">
                <span class="name mr-1">Mark Webber</span>
                reacted to your recent post
                <span class="hover f800 ml-1">
                    My first tournament today!
                </span>
                <div class="ml-2 bg-red-500 h-2 w-2 rounded-full" />
            </span> -->
            <span class="block">1m ago</span>
        </div>
    </div>

    <!-- 2 -->
    <div class="rounded-lg p-3 unread flex items-start gap-2">
        <img
            class="cursor-pointer"
            height="50"
            width="50"
            src="notifi/2.webp"
            alt="avatar"
        />
        <div>
            <span class="flex items-center">
                <b class="name mr-1"> Angela Gray </b>
                followed you
                <div class="ml-2 bg-red-500 h-2 w-2 rounded-full" />
            </span>
            <span class="block">5m ago</span>
        </div>
    </div>

    <!-- 3-->
    <div class="rounded-md p-3 unread flex items-start gap-2">
        <img
            class="cursor-pointer"
            height="50"
            width="50"
            src="notifi/4.webp"
            alt="avatar"
        />
        <div>
            <span class="flex items-center">
                <b class="name mr-1">Jacob Thompson</b>
                has joined your group
                <span class="hover f800 ml-1"> Chess Club </span>
                <div class="ml-2 bg-red-500 h-2 w-2 rounded-full" />
            </span>
            <span class="block">1 day ago</span>
        </div>
    </div>
    <!-- 4-->

    <div class="rounded-md p-3 unread flex items-start gap-2">
        <img
            class="cursor-pointer"
            height="50"
            width="50"
            src="notifi/6.webp"
            alt="avatar"
        />
        <div>
            <span class="name">Mark Webber</span>
            <span>reacted to your recent post</span>
            <span class="flex items-center hover f800"
                >My first tournament today!
                <div class="ml-2 bg-red-500 h-2 w-2 rounded-full" />
            </span>
            <span class="block">1m ago</span>
        </div>
    </div>
    <!-- 5-->

    <div class="rounded-md p-3 unread flex items-start gap-2">
        <img
            class="cursor-pointer"
            height="50"
            width="50"
            src="notifi/6.webp"
            alt="avatar"
        />
        <div>
            <span class="name">Mark Webber</span>
            <span>reacted to your recent post</span>
            <span class="flex items-center hover f800"
                >My first tournament today!
                <div class="ml-2 bg-red-500 h-2 w-2 rounded-full" />
            </span>
            <span class="block">1m ago</span>
        </div>
    </div>
    <!-- 6-->

    <div class="rounded-md p-3 unread flex items-start gap-2">
        <img
            class="cursor-pointer"
            height="50"
            width="50"
            src="notifi/6.webp"
            alt="avatar"
        />
        <div>
            <span class="name">Mark Webber</span>
            <span>reacted to your recent post</span>
            <span class="flex items-center hover f800"
                >My first tournament today!
                <div class="ml-2 bg-red-500 h-2 w-2 rounded-full" />
            </span>
            <span class="block">1m ago</span>
        </div>
    </div>
    <!-- 7-->

    <div class="rounded-md p-3 unread flex items-start gap-2">
        <img
            class="cursor-pointer"
            height="50"
            width="50"
            src="notifi/6.webp"
            alt="avatar"
        />
        <div>
            <span class="name">Mark Webber</span>
            <span>reacted to your recent post</span>
            <span class="flex items-center hover f800"
                >My first tournament today!
                <div class="ml-2 bg-red-500 h-2 w-2 rounded-full" />
            </span>
            <span class="block">1m ago</span>
        </div>
    </div>
</div>

<style>
    @import url("https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@500;800&display=swap");
    :root {
        --VerylightGrayishBlue: hsl(210, 60%, 98%);
        --LightGrayishBlue1: hsl(211, 68%, 94%);
        --LightGrayishBlue2: hsl(205, 33%, 90%);
        --GrayishBlue: hsl(219, 14%, 63%);
        --DarkGrayishBlue: hsl(219, 12%, 42%);
        --VeryDarkBlue: hsl(224, 21%, 14%);
    }
    :global(html) {
        background-color: var(--VerylightGrayishBlue);
    }

    .f800 {
        font-weight: 800 !important;
    }
    h4,
    span {
        font-family: "Plus Jakarta Sans", sans-serif;
    }
    .name {
        font-weight: 800;
        color: var(--VeryDarkBlue);
        cursor: pointer;
    }
    span {
        font-weight: 500;
        color: var(--DarkGrayishBlue);
    }
    .hover:hover {
        color: var(--VeryDarkBlue);
        cursor: pointer;
    }
    .count {
        background-color: rgba(0, 0, 128, 0.849);
        color: white;
        padding: 0 8px;
        border-radius: 5px;
    }
    .unread {
        background-color: var(--LightGrayishBlue1);
    }
    .dot::after {
        content: ".";
        color: red;
        font-size: xx-large;
        line-height: 0;
    }
</style>
