Language
=======================
You can modify the default language files and even create your own language files.

.. note::

   The following languages are available by default:

   - English (``en``)
   - German (``de``)
   - French (``fr``)
   - Spanish (``es``)


Modify language files
---------------------

1. Create a JSON file with the prefix ``ez_`` somewhere in your project.

   - If you want to modify the English language file: ``ez_en.json``.
   - If you want to create a new language file: ``ez_[language].json``.

   For example, if you want to create a French language file, the file name could be ``ez_fr.json``.

2. Copy the contents of a :ref:`language file <language>` into your new file and modify it.
3. Pass the language string into :meth:`~ezcord.bot.Bot` to set your language.

.. code-block:: python

   bot = ezcord.Bot(language="fr")  # French (loaded from ez_fr.json)


.. _language:

Language files
--------------

.. literalinclude:: ../../ezcord/internal/language/en.json
   :language: python
   :caption: The default language file for English.

.. literalinclude:: ../../ezcord/internal/language/de.json
   :language: python
   :caption: The default language file for German.

.. literalinclude:: ../../ezcord/internal/language/fr.json
   :language: python
   :caption: The default language file for French.

.. literalinclude:: ../../ezcord/internal/language/es.json
   :language: python
   :caption: The default language file for Spanish.
