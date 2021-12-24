# Alex Zakrevsky
*******
## Contacts:
* **Discord**: Sa`Neal
* **E-mail**: zakrevskyalex1323@gmail.com
*******
## About myself:
My name is Alex and I just love computer stuff, it has been with me throught my life, and recently I found out that I love to code! Algorithms writing/optimization, problem solving, coming up with the most efficient way of perfoming a task and constant learning - this is what I am all about right now. By the way, I have a 5 year experience of video montage/photo editing and coding is a new page, not to say a book, in my career. I try to learn as much as I can and from as many different sources as there are available. My main task for now is to choose my future specification in IT, so I`m looking forward to learn front-end in RS School!

## Code Example (Function of deleting a tree node in Bin Search Tree(C++)):

		if (tmp->right != NULL)
		{
			if (tmp == tmp->parent->right) tmp->parent->right = tmp->right;
			if (tmp == tmp->parent->left) tmp->parent->left = tmp->left;
			tmp->parent = searched->parent;
			searched->left->parent = tmp;
			tmp->left = searched->left;
			if (searched == searched->parent->left) searched->parent->left = tmp;
			if (searched == searched->parent->right) searched->parent->right = tmp;
			delete searched;
			return;
		}

	}

	if ((searched->left == NULL) && (searched->right != NULL))
	{
		tmp = searched->parent;
		if (searched == tmp->right) tmp->right = searched->right;
		if (searched == tmp->left) tmp->left = searched->right;
		searched->right->parent = tmp;
		delete(searched);
		return;
	}

	if ((searched->left != NULL) && (searched->right == NULL))
	{
		tmp = searched->parent;
		if (searched == tmp->right) tmp->right = searched->left;
		if (searched == tmp->left) tmp->left = searched->left;
		searched->left->parent = tmp;
		delete(searched);
		return;
	}
	return;

## Skills:
* C++ (intermediate)
* HTML/CSS (beginner)
* JS (basic knowledge)
* Adobe Photoshop, Premiere Pro, After Effects (intermediate)

## Projects:
This CV is my first uploaded-to-net project.

## English:
* 96 CT
* 78 EFSET
![EF SET Certificate cut](https://user-images.githubusercontent.com/94646827/147333133-c3d8c244-eb42-4def-a52c-ce516d0b26cd.png)

