---
layout: default
---
<body>
{%- assign latest_post = site.posts[0] -%}
<p>Redirecting you to {{ latest_post.title }}</p>

<script>
    window.location.href = "{{ latest_post.url }}";
</script>

</body>