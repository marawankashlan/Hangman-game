# Hangman-game
#include "stdafx.h"
#include<iostream>
#include <string>
#include <algorithm>
#include <vector>
#include <sstream>
#include <fstream>
#include<SFML/Graphics.hpp>
#include<SFML/Audio.hpp>
using namespace std;
using namespace sf;
class hangman
{

public:
	hangman();
	void gui();
	bool isSpriteHover(FloatRect sprite, Vector2f mousePos);
	vector<string> random(string menu);
	vector<string> movies(string menu);
	vector<string>tvs(string menu);
	vector<string> sport(string menu);
	vector<string> split(const string& s, char delimiter);
};
