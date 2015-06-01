###Serialize Object (Output)

  	try {
		ObjectOutput out = new ObjectOutputStream(IOUtils.createObjectXZBufferedOutputStream(FILEPATH);
		try {
			out.writeObject(OBJECT);
		} finally {
			out.close();
		}
	} catch (Exception e) { e.printStackTrace(); }
	
###Deserialize Object (Input)

	try {
		ObjectInput in = new ObjectInputStream(IOUtils.createObjectXZBufferedInputStream(FILEPATH);
		try {
			OBJECT_TYPE object = (OBJECT_TYPE) in.readObject();
		} finally {
			in.close();
		}
	} catch (Exception e) { e.printStackTrace(); }
