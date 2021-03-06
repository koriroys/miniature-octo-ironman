Overview
--------

I want to be able to make ruby-monk style lessons
e.g. https://rubymonk.com/learning/books/4-ruby-primer-ascent/chapters/44-collections/lessons/98-iterate-filtrate-and-transform
This project is to support that.

Getting started
---------------

<table>
  <tr>
    <td> Install dependencies with </td>
    <td> <code>rake bootstrap</code> </td>
  </tr>
  <tr>
    <td> Run tests with </td>
    <td> <code>rake cuke</code> </td>
  </tr>
  <tr>
    <td> Run server with </td>
    <td> <code>rake server</code> (once someone does <a href="https://github.com/JoshCheek/miniature-octo-ironman/issues/11"> Rake task for server</a> anyway) </td>
  </tr>
</table>

Iteration 1 goals
-----------------

- [X] I can embed a Ruby snippet into a markdown page and see an editor
- [ ] I can run the code in the editor and see the output (Follow along with progress at #12)

How do I contribute?
--------------------

* Pick an [issue](https://github.com/JoshCheek/miniature-octo-ironman/issues):
  * Look for one that is not assigned
  * Sub issues of [#12][issue12] would be super helpful :)
  * Also, [#2][issue2], [#11][issue11], and [#17][issue17] are small
* Make a branch to implement the feature
* If it needs tests, make sure it is tested, either way, make sure it doesn't break existing tests, we are currently passing through [this](https://github.com/JoshCheek/miniature-octo-ironman/blob/b308eb4fff2734dd79963471283681cd6e829bbe/features/omg.feature#L15) step
* Send pull request (from your branch to master, if you have commit rights, or from your repo to our master if you don't)
* After code review, merge it
* Delete the branch


Future shit maybe
-----------------

* manifest of lesson names to git repositories (ie gist) rather than having to edit the source of the server to change a lesson
* maybe scoped by content owner
* maybe overridable language for the editor


[issue2]:  https://github.com/JoshCheek/miniature-octo-ironman/issues/2
[issue11]: https://github.com/JoshCheek/miniature-octo-ironman/issues/11
[issue12]: https://github.com/JoshCheek/miniature-octo-ironman/issues/12
[issue17]: https://github.com/JoshCheek/miniature-octo-ironman/issues/17

