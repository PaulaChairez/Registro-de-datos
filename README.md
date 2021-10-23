# Registro-de-datos
import xml.etree.cElementTree as et 

root = et.Element("Alumno2")
root = et.Element("edif2")
se = et.SubElement (root, "Desarrollo de software")
et.SubElement(se, "Nombre").text="Paula chairez Vazquez"
et.SubElement(se, "Matricula").text="18040021"

root = et.Element("edif2")
se = et.SubElement (root, "Desarrollo de software")
et.SubElement(se, "Nombre").text="Juan Hernandez"
et.SubElement(se, "Matricula").text="18040022"

root = et.Element("edif2")
se = et.SubElement (root, "Desarrollo de software")
et.SubElement(se, "Nombre").text="Iliana Herrera Guerrero "
et.SubElement(se, "Matricula").text="18040055"


root = et.Element("edif2")
se = et.SubElement (root, "Desarrollo de software")
et.SubElement(se, "Nombre").text="Jesus Serna James"
et.SubElement(se, "Matricula").text="18040033"

root = et.Element("edif2")
se = et.SubElement (root, "Desarrollo de software")
et.SubElement(se, "Nombre").text="Nicolas Ramirez "
et.SubElement(se, "Matricula").text="18040044"

root = et.Element("edif2")
se = et.SubElement (root, "Multimedia")
et.SubElement(se, "Nombre").text="Briseidi Garza "
et.SubElement(se, "Matricula").text="18040088"

root = et.Element("edif2")
se = et.SubElement (root, "Multimedia")
et.SubElement(se, "Nombre").text="Roberto Hernandez Arroyo"
et.SubElement(se, "Matricula").text="18040029"

root = et.Element("edif2")
se = et.SubElement (root, "Multimedia")
et.SubElement(se, "Nombre").text="Elvira Vazquez "
et.SubElement(se, "Matricula").text="18040042"

root = et.Element("edif2")
se = et.SubElement (root, "Multimedia")
et.SubElement(se, "Nombre").text="Daniel Guevara "
et.SubElement(se, "Matricula").text="18040088"

root = et.Element("edif2")
se = et.SubElement (root, "Multimedia")
et.SubElement(se, "Nombre").text="Maria Martinez Montes"
et.SubElement(se, "Matricula").text="18040011"

root = et.Element("edif2")
se = et.SubElement (root, "Redes")
et.SubElement(se, "Nombre").text="Alejandro Briones Juarez "
et.SubElement(se, "Matricula").text="18040006"

root = et.Element("edif2")
se = et.SubElement (root, "Redes")
et.SubElement(se, "Nombre").text="Jose Ponce Bustos "
et.SubElement(se, "Matricula").text="18040020"

root = et.Element("edif2")
se = et.SubElement (root, "Redes")
et.SubElement(se, "Nombre").text="Viviana Chaires Ponce "
et.SubElement(se, "Matricula").text="18040057"

root = et.Element("edif2")
se = et.SubElement (root, "Redes")
et.SubElement(se, "Nombre").text="Roberto Vazquez"
et.SubElement(se, "Matricula").text="18040055"

root = et.Element("edif2")
se = et.SubElement (root, "Redes")
et.SubElement(se, "Nombre").text="Alfonso Marquez"
et.SubElement(se, "Matricula").text="18040086"

tree = et.ElementTree(root)
tree.write("Alumno2.xml", xml_declaration=True)
