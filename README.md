# `tilde` - user script tilde-launcher

```
wrapper for user-submitted scripts
supports user submission and admin approval

usage: tilde [help|list|submit|about|<script_name>]

  tilde list                 - show a list of approved userscripts
  tilde submit               - start the submission flow for your own script
  tilde about <script_name>  - get the description for script_name
  tilde <script_name>        - run script_name with all remaining args are passed to the script
```

approved scripts are placed in /tilde/bin and listed with `tilde list`

submissions use sendmail to notify an admin.

admins can use `sudo tilde approve` and `sudo tilde revoke <script_name>`.
