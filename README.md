# django-change-lang
Change lang in django

```
{% load lang_tags staticfiles i18n %}

{% get_available_languages as LANGUAGES %}
{% for language_code, language_name in LANGUAGES %}
	<a href="{% change_lang language_code %}">{{ language_name }}</a>
{% endfor %}
```
