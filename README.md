# Getting-DDL-Attribute-Dynamically
A short example on how to get Liferay DDL attributes dynamically in Freemarker, Java and Velocity Marker


In the examples the trick is to get the DDL records using  'DDLRecordLocalServiceUtil' library of liferay.
After doing so the Field values can then be gotten as serializable object and the cast to the appropriate datatype for the attribute.
