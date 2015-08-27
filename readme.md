Q: given an array of objects with the format of:

	{

		title: '',

		body: '',

		created: '',

		user: {

		    name: '',

		    id: #

		}

	}

with efficiency in mind, write a function that returns an array of objects in the format of:

	{

		name: '',

		last_post_title: ''

	}

containing the 30 most frequent posters of the last 3 months, sorted by the last time they posted.