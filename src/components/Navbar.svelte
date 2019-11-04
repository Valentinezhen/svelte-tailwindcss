<script>
  import { Link } from "svero";
</script>

<nav class="relative select-none bg-grey lg:flex lg:items-stretch w-full">
  <div class="flex flex-no-shrink items-stretch h-12 ">
    <Link
      href="/"
      class="flex-no-grow flex-no-shrink relative py-2 px-4 leading-normal
      text-white no-underline flex items-center hover:bg-grey-dark">
      Soonlinmas
    </Link>

  </div>
  <div class="lg:flex lg:items-stretch lg:flex-no-shrink lg:flex-grow">
    <div class="lg:flex lg:items-stretch lg:justify-end ml-auto">
      <Link
        href="/products"
        class="flex-no-grow flex-no-shrink relative py-2 px-4 leading-normal
        text-white no-underline flex items-center hover:bg-grey-dark">
        Products
      </Link>
      <a
        href="#"
        class="flex-no-grow flex-no-shrink relative py-2 px-4 leading-normal
        text-white no-underline flex items-center hover:bg-grey-dark">
        Gallery
      </a>
      <a
        href="#"
        class="flex-no-grow flex-no-shrink relative py-2 px-4 leading-normal
        text-white no-underline flex items-center hover:bg-grey-dark">
        Contact
      </a>
    </div>
  </div>
</nav>
