=========================
List
=========================

| 角カッコの中にカンマ区切りの要素を入れる。
| 異なる型のアイテムを入れられるが、通常は全て同じ型を入れる。
| インデックスとスライシングが使える。
| 変更可能体（mutable）


.. code-block:: python

  >>> #空リスト
  >>> x = []
  >>> print(type(x))
  <class 'list'>

.. code-block:: python

  >>> #連結
  >>> [1, 2, 3, 4] + [5, 6, 7, 8]
  [1, 2, 3, 4, 5, 6, 7, 8]



.. code-block:: python

  >>> #ネスト
  >>> food = ['apple', 'biscuits', 'cookie']
  >>> number = [1, 2, 3]
  >>> treat = [food, number]
  >>> treat
  [['apple', 'biscuits', 'cookie'], [1, 2, 3]]
  >>> x[0]
  ['apple', 'biscuits', 'cookie']
  >>> x[0][1]
  'biscuits'



| 

**Method**

.. toctree::
   :maxdepth: 1

   list.append(x)
   list.extend(L)


| 

