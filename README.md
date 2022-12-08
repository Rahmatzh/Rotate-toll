//tol
public closetollv2()
{
    for(new i=0; i<MAX_PLAYERS; i++)
	{
		if (IsPlayerConnected(i))
		{
	    	RotateObject(tollv2, 0, 269.39801025391, 341.33288574219, 20, 11.5);
	    }
    }
    return 1;
}


public closetollv1()
{
    for(new i=0; i<MAX_PLAYERS; i++)
	{
		if (IsPlayerConnected(i))
		{
	    	RotateObject(tollv1, 0, 89.173858642578, 342.47998046875, 20, 11.5);
	    }
    }
    return 1;
}


public closetol1()
{
    for(new i=0; i<MAX_PLAYERS; i++)
	{
		if (IsPlayerConnected(i))
		{
	    	RotateObject(tol1, 0, 90, 89, 20, 11.5);
	    }
    }
    return 1;
}

public closetol2()
{
    for(new i=0; i<MAX_PLAYERS; i++)
	{
		if (IsPlayerConnected(i))
		{
	    	RotateObject(tol2, 0, 269, 89, 20, 11.5);
	    }
    }
    return 1;
}

public closetol3()
{
    for(new i=0; i<MAX_PLAYERS; i++)
	{
		if (IsPlayerConnected(i))
		{
	    	RotateObject(tol3, 359.89801025391, 90.713226318359, 333.55590820313, 20, 11.5);
	    }
    }
    return 1;
}

public closetol4()
{
    for(new i=0; i<MAX_PLAYERS; i++)
	{
		if (IsPlayerConnected(i))
		{
	    	RotateObject(tol4, 358.24392700195, 268.52798461914, 333.34854125977, 20, 11.5);
	    }
    }
    return 1;
}

public OnObjectRotated(objectid)
{
    return 1;
}

public OnObjectStopRotate(objectid)
{
    return 1;
}
