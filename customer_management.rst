.. _user-guide-accounts:

Accounts
========

Accounts View Page
^^^^^^^^^^^^^^^^^^

If an account relates to a Magento customer, its view page will have the **Magento** section displayed. Its subsections will be the following:

1. The *General Info* subsection has the general information on the Magento customer related to the account (e.g. name, email, customer group, website, etc.)

2. The *Magento Orders* subsection lists all the :ref:`orders <user-guide-magento-orders-create>` related to the account.

3. The *Magento Purchases* subsection gives a quick overview of the products that the customer recently purchased. Products disappear from the list if an order is cancelled or deleted on the Magento side.

4. The *Magento Shopping Carts* subsection shows the details of the :ref:`shopping carts <user-guide-magento-carts-create>` related to the account.

5. The *Magento Credit Memos* subsection is for :ref:`credit memo <user-guide--sales--magento-credit-memos>` and order details, such as the store from which the order has been placed, order number, the amount refunded, etc.

6. The *Magento Order Notes* subsection show the comments added to an order on the Magento side as notes in Oro.

     .. image:: /img/accounts/account_subsections_new2.png

Channels
^^^^^^^^

A Magento channel is required to enable Magento integration and work with Magento related data. More information on this can be found in the relevant :ref:`Magento channels <user-guide-magento-channel>` amd :ref:`Magento-based sales <doc-magento-based-sales>` topics.

Customers
^^^^^^^^^

Each profile within one channel is a *customer*. However, the type of customers depends on the type of channels that they arrived from. For profiles that come from Magento, these are **Magento Customers**.

.. image:: /img/accounts/accounts_view_channels.png


