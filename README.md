#include <iostream>
#include <list>
#include <algorithm>

using namespace std;

class Persona
{
public:
	string name;
	string ine;
	string genero;
	string nacionalidad;
	string fechadenacimiento;
	int idPersona;
	int idedad;
public:
	Persona(string nombre, int id);
	void Muestra();
	void asignar(string name, int idedad, string fechadenacimiento, string ine, string genero, string nacionalidad,
		int idPersona);
};



int main(int argc, const char* argv[])
{
	string name;
	string ine;
	string genero;
	string nacionalidad;
	string fechadenacimiento;
	int idPersona;
	int idedad;

	Persona p1("Juan Jose", 1);
	Persona p2("Roberto Gomez", 2);
	Persona p3("Jose Alfredo", 3);
	Persona p4("Checo Perez", 4);
	Persona p5("Chabelo", 5);
	p1.asignar("Juan Jose", 20, "12 / 12 / 2000", "201202jerosepan", "mujer", "Tierra media", 1);
	p2.asignar("Roberto Gomez", 27, "12 / 11 / 1994", "1294roertgmoez", "hombre", "Gotham city", 2);
	p3.asignar("Jose Alfredo", 30, "12 / 11 / 1991", "1991joseal11", "hombre", "americano", 3);
	p4.asignar("Checo Perez", 22, "03 / 8 / 1999", "1999checo22sdferpes", "hombre", "frances", 4);
	p5.asignar("Chabelo", 89, "17/02/1935", "3519beloxavipez234", "hombre", "iran", 5);

	std::cout << "Escriba el nombre: ";
	std::cin >> name;
	if (p1.name == name)
	{
		std::cout << "Escriba la edad: ";
		std::cin >> idedad;
		if (p1.idedad == idedad)
		{
			std::cout << "Escriba la fecha de nacimiento: ";
			std::cin >> fechadenacimiento;
			if (p1.fechadenacimiento == fechadenacimiento)
			{
				std::cout << "Escriba la ine: ";
				std::cin >> ine;
				if (p1.ine == ine)
				{
					std::cout << "Escriba el genero: ";
					std::cin >> genero;
					if (p1.genero == genero)
					{
						std::cout << "Escriba la nacionalidad";
						std::cin >> nacionalidad;
						if (p1.nacionalidad == nacionalidad)
						{
						}
						else std::cout << "es terrorista";
					}
					else std::cout << "es terrorista";

				}
				else std::cout << "es terrorista";
			}
			else std::cout << "es terrorista";
		}
		else std::cout << "es terrorista";
	}
	else std::cout << "es teorrista";


	std::cout << "Escriba el nombre: ";
	std::cin >> name;
	if (p2.name == name)
	{
		std::cout << "Escriba la edad: ";
		std::cin >> idedad;
		if (p2.idedad == idedad)
		{
			std::cout << "Escriba la fecha de nacimiento: ";
			std::cin >> fechadenacimiento;
			if (p2.fechadenacimiento == fechadenacimiento)
			{
				std::cout << "Escriba la ine: ";
				std::cin >> ine;
				if (p2.ine == ine)
				{
					std::cout << "Escriba el genero: ";
					std::cin >> genero;
					if (p2.genero == genero)
					{
						std::cout << "Escriba la nacionalidad";
						std::cin >> nacionalidad;
						if (p2.nacionalidad == nacionalidad)
						{
						}
						else std::cout << "es terrorista";
					}
					else std::cout << "es terrorista";

				}
				else std::cout << "es terrorista";
			}
			else std::cout << "es terrorista";
		}
		else std::cout << "es terrorista";
	}
	else std::cout << "es terrorista";


	std::cout << "Escriba el nombre: ";
	std::cin >> name;
	if (p3.name == name)
	{
		std::cout << "Escriba la edad: ";
		std::cin >> idedad;
		if (p3.idedad == idedad)
		{
			std::cout << "Escriba la fecha de nacimiento: ";
			std::cin >> fechadenacimiento;
			if (p3.fechadenacimiento == fechadenacimiento)
			{
				std::cout << "Escriba la ine: ";
				std::cin >> ine;
				if (p3.ine == ine)
				{
					std::cout << "Escriba el genero: ";
					std::cin >> genero;
					if (p3.genero == genero)
					{
						std::cout << "Escriba la nacionalidad: ";
						std::cin >> nacionalidad;
						if (p3.nacionalidad == nacionalidad)
						{
						}
						else std::cout << "No es terrorista";

					}
					else std::cout << "No es terrorista";

				}
				else std::cout << "No es terrorista";
			}
			else std::cout << "No es terrorista";

		}
		else std::cout << "No es terrorista";

	}
	else std::cout << "No es terrorista";

	std::cout << "Escriba el nombre: ";
	std::cin >> name;
	if (p4.name == name)
	{
		std::cout << "Escriba la edad: ";
		std::cin >> idedad;
		if (p4.idedad == idedad)
		{
			std::cout << "Escriba la fecha de nacimiento: ";
			std::cin >> fechadenacimiento;
			if (p4.fechadenacimiento == fechadenacimiento)
			{
				std::cout << "Escriba la ine: ";
				std::cin >> ine;
				if (p4.ine == ine) {
					std::cout << "Escriba el genero: ";
					std::cin >> genero;
					if (p4.genero == genero)
					{
						std::cout << "Escriba la nacionalidad";
						std::cin >> nacionalidad;
						if (p4.nacionalidad == nacionalidad)
						{
						}
						std::cout << "No es terrorista";

					}
					else std::cout << "No es terrorista";
				}
				else std::cout << "No es terrorista";
			}
			else std::cout << "No es terrorista";
		}
		else std::cout << "No es terrorista";
	}
	else std::cout << "No es terrorista";



	std::cout << "Escriba el nombre: ";
	std::cin >> name;
	if (p5.name == name)
	{
		std::cout << "Escriba la edad: ";
		std::cin >> idedad;
		if (p5.idedad == idedad)
		{
			std::cout << "Escriba la fechadenacimiento: ";
			std::cin >> fechadenacimiento;
			if (p5.fechadenacimiento == fechadenacimiento)
			{
				std::cout << "Escriba la ine: ";
				std::cin >> ine;
				if (p5.ine == ine)
				{
					std::cout << "Escriba el genero: ";
					std::cin >> genero;
					if (p5.genero == genero)
					{
						std::cout << "Escriba la nacionalidad: ";
						std::cin >> nacionalidad;
						if (p5.nacionalidad == nacionalidad)
						{
						}
						else std::cout << "No es terrorista";
					}
					else std::cout << "No es terrorista";
				}
				else std::cout << "No es terrorista";
			}
			else std::cout << "No es terrorista";
		}
		else std::cout << "No es terrorista";
	}
	else std::cout << "No es terrorista";







}


void Persona::asignar(string name, int idedad, string fechadenacimiento, string ine, string genero, string nacionalidad, int idPersona)
{
	this->name = name;
	this->idedad = idedad;
	this->fechadenacimiento = fechadenacimiento;
	this->ine = ine;
	this->genero = genero;
	this->nacionalidad = nacionalidad;
	this->idPersona = idPersona;
	this->nacionalidad = nacionalidad;
}
