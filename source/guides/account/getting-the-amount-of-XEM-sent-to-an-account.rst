:orphan:

############################################
Getting the amount of XEM sent to an account
############################################

Check the amount of XEM you have sent to some account.

*************
Prerequisites
*************

- Finish the :doc:`getting started section <../../getting-started/setup-workstation>`
- Text editor or IDE
- NEM2-SDK or CLI

************************
Let’s get into some code
************************

After obtaining all outgoing :doc:`transactions <../../concepts/transaction>` from an account, apply the following operators to identify the target recipient.

.. example-code::

    .. literalinclude:: ../../resources/examples/typescript/account/GettingTheAmountOfXEMSentToAnAccount.ts
        :language: typescript
        :lines:  23-

    .. literalinclude:: ../../resources/examples/java/src/test/java/nem2/guides/examples/account/GettingTheAmountOfXEMSentToAnAccount.java
        :language: java
        :lines: 40-66

    .. literalinclude:: ../../resources/examples/javascript/account/GettingTheAmountOfXEMSentToAnAccount.js
        :language: javascript
        :lines: 28-

The amount of sent XEM in transfer transactions is displayed.

************
What’s next?
************

Repeat the example by changing NEM filter for another :doc:`mosaic <../../concepts/mosaic>` .