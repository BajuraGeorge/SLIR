# SLIR watermarking patch
This patch enhances the original SLIR (https://github.com/lencioni/SLIR) with watermarking capabilities.

# Setting up
In your `slirconfig.class.php` file, add the following:

    self::$watermark = true; // true to enable watermarking, false otherwise
    self::$watermarkFile = path_to_stamp_file.jpg;


# Using
<table>
  <thead>
    <tr>
      <th>Parameter</th>
      <th>Mearning</th>
      <th>Example</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><var>wm</var></td>
      <td>Activate watermarking</td>
      <td><code>slir/?<strong>wm=1</strong>&w=344&h=344&i=image.jpg</code></td>
    </tr>
  </tbody>
</table>
