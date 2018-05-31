=================
Java Server Pages
=================

JSTL
====

if
---

.. code:: jsp
   
   <c:if test="${<conditon>}">
    ...
   </c:if>

if else / choose
-----------------

.. code:: jsp
   
   <c:choose>
     <c:when test="${condition1}">
       ...
     </c:when>
     <c:when test="${condition2}">
       ...
     </c:when>
     <c:otherwise>
       ...
     </c:otherwise>
   </c:choose>
