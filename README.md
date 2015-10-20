# flushot_clinic
Drupal custom module to autopopulate flushot clinic registration form fields based on CruzID Blue user object.

This module works in conjunction with the soe_blue_auth module under Drupal 7.
Upon successful LDAP bind using user CruzID Blue credentials, an authenticated user object containing LDAP data can be accessed
to autopopulate form fields in a registration form using Drupal's hook_form_alter().
