<script>
  import Icon from "svelte-awesome/components/Icon.svelte";
  import { at, instagram, whatsapp } from "svelte-awesome/icons";
</script>

<footer class="footer">
  <div class="content has-text-centered">
    <Icon data={at} scale="2" />
    <Icon data={instagram} scale="2" />
    <Icon data={whatsapp} scale="2" />
    <p>
      <strong>Bulma</strong>
      by
      <a href="https://jgthms.com">Jeremy Thomas</a>
      . The source code is licensed
      <a href="http://opensource.org/licenses/mit-license.php">MIT</a>
      . The website content is licensed
      <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/">
        CC BY NC SA 4.0
      </a>
      .
    </p>

  </div>
</footer>
