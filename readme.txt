��ʹ�÷�����
Usage: 
mesh_animate input                			        Create an animation to compare the algorithms. 
mesh_show mode input percentage           			Reduce input model to percentage, show the image.
mesh_model mode input output percentage				Output the reduced model to output.

Mode Parameters:
        l						        use edge length as cost function. v=(v1+v2)/2.
        q							use the quadratic cost function. v=(v1+v2)/2.
        qopt     						use the quadratic cost function. v is optimal.

Examples:
mesh_animate sphere.obj						Create an animation of reducing sphere.obj from the original to zero faces.
mesh_show q sphere.obj 20					Show the result of reducing sphere.obj to 20% faces.	
mesh_model qout sphere.obj sphere_opt.obj 20			Output the result of reducing sphere.obj to 20% faces to sphere_opt.obj

������˵����
����ģʽ��
  |	��	��
--+---------------------------
��|	ԭʼ	�߳���
��|	����	���Σ�����v��

��ʾģʽ��
ʹ�á��������������ת�ӽǡ�

ע�⣺
���������ʹ�����Ҫ����ʱ�䣬���ʱ���ڿ��������򴰿ڣ������ĵȴ���

��������
OpenGL��ʾ���֣�ʹ����Jeff Molofee (NeHe)��OpenGLʾ�������еĴ���
http://nehe.gamedev.net/tutorial/3d_shapes/10035/

�����롿
��ʹ��Visual Studio 2010���빤�̡�

Project �ļ����а�����

��  MeshOptimizing.sln			VS2010�������
��  
����MeshOptimizing
        animate.cpp			����������
        LinearEquation_Special.cpp	������Է�����
        LinearEquation_Special.h
        Mesh.cpp			�����������
        Mesh.h
        MeshOptimizing.vcxprojVS2010����
        MeshOptimizing.vcxproj.filters
        MeshOptimizing.vcxproj.user
        model.cpp			ģ�����������
        show.cpp			��ʾ��̬ģ��������
        SimpleObject.cpp		.Obj Parser
        SimpleObject.h
        Vec3f.cpp
        Vec3f.h
        
