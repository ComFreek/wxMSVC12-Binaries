wxMSVC12-Binaries
=================

wxWidgets binaries built with MSVC 2012 For Desktop

Here are the combinations I've used:
<table>
  <tr>
    <th>Flags</th>

    <th>Description</th>
  </tr>

  <tr>
    <td><tt>SHARED=0 BUILD=debug</tt></td>

    <td>Builds static debug libraries.</td>
  </tr>

  <tr>
    <td><tt>SHARED=0 BUILD=release</tt></td>

    <td>Builds static release libararies.</td>
  </tr>

  <tr>
    <td><tt>SHARED=1 BUILD=debug</tt></td>

    <td>Builds dynamic debug libraries.</td>
  </tr>

  <tr>
    <td><tt>SHARED=1 BUILD=release</tt></td>

    <td>Builds dynamic release libraries.</td>
  </tr>

  <tr>
    <td><tt>SHARED=1 MONOLITHIC=1 BUILD=debug</tt></td>

    <td>Builds one big, dynamic debug library.</td>
  </tr>

  <tr>
    <td><tt>SHARED=1 MONOLITHIC=1 BUILD=release</tt></td>

    <td>Builds one big, dynamic release library.</td>
  </tr>
</table>


License
=======
These binaries are under the same license as described on the wxWidgets website.
See wxWindow.LICENSE and LGPL.LICENSE for more information.