---
layout: settings
title: Settings - Deactivate
---

<p>Permanently delete your account and all of your content.</p>

<form>

{% include form/checkbox.html id="agreement" value=0 label="I understand" %}

<br>
<br>

<br>

<!-- Accent-colored raised button with ripple -->
<a class="mdl-button mdl-js-button mdl-button--raised mdl-js-ripple-effect mdl-button--accent" href="/auth/sign-out">
    Delete
</a>

</form>