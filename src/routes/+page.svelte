{#snippet test(parameter)}
  {parameter}
{/snippet}

{@render test("a")}
<!-- Execute `npm run format` to watch the following line get mangled -->
{@render test((()=>"a")())}