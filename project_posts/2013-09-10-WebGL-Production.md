# WebGL Version Production

It needs to be converted to WebGL because : 

1. Performance Issue
2. Public access without boundaries
3. Easy Artwork Installation Process(Just need a Chrome Browser)

As Performance Issue, I don't use Three.js, the most famous WebGL Library but 
modifying Graph engine. 

```
  render : function () {
      if (permit_rendering) {
          update_label_position(transform);
     
          gl.useProgram(program);
          gl.bindBuffer(gl.ARRAY_BUFFER, buffer);
          gl.bufferData(gl.ARRAY_BUFFER, storage, gl.DYNAMIC_DRAW);


          if (sizeDirty) {
              sizeDirty = false;
              gl.uniformMatrix4fv(locations.transform, false, transform);
              gl.uniform2f(locations.screenSize, width, height);
         }

          gl.vertexAttribPointer(locations.vertexPos, 2, gl.FLOAT, false, 3 * 4, 0);
          gl.vertexAttribPointer(locations.color, 4, gl.UNSIGNED_BYTE, true, 3 * 4, 2 * 4);

          gl.bindBuffer(gl.ELEMENT_ARRAY_BUFFER, indicesBuffer);
          gl.bufferData(gl.ELEMENT_ARRAY_BUFFER, indices, gl.DYNAMIC_DRAW);
        //  gl.drawArrays(gl.LINE_STRIP, positions.length / 3, 0);
          gl.drawElements(gl.TRIANGLES, indices_length_offset, gl.UNSIGNED_BYTE, 0);
      } 
      vertices_length_offset = 0;
      indices_length_offset = 0;
  }
```

## Explore Creators 

![WebGL Creator 03](../project_images/04_webgl_production/creator_03.png?raw=true "WebGL Creator 03")

![WebGL Creator 01](../project_images/04_webgl_production/creator_01.png?raw=true "WebGL Creator 01")

![WebGL Creator 02](../project_images/04_webgl_production/creator_02.png?raw=true "WebGL Creator 02")



## Shortest Path Finding

![WebGL Connection 01](../project_images/04_webgl_production/connection_01.png?raw=true "WebGL Connection 01")

![WebGL Connection 02](../project_images/04_webgl_production/connection_02.png?raw=true "WebGL Connection 02")

![WebGL Connection 03](../project_images/04_webgl_production/connection_03.png?raw=true "WebGL Connection 03")




## Show Communities 

![WebGL Community 01](../project_images/04_webgl_production/community_01_01.png?raw=true "WebGL Community 01")

![WebGL Community 02](../project_images/04_webgl_production/community_02_02.png?raw=true "WebGL Community 02")

![WebGL Community 03](../project_images/04_webgl_production/community_02_02.png?raw=true "WebGL Community 03")


