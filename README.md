underwater
==========

				program.prp= gl.getUniformLocation(program, "prp");

				// Update camera
				gl.uniform3fv(program.prp, [12.0*Math.cos(time * 0.1), 1.0+0.9*Math.sin(time*0.05), 12.0*sin(time * 0.1)]);
				