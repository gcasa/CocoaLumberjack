#
#  Copyright (C) 1997 Free Software Foundation, Inc.
#
#  Written by:	Scott Christley <scottc@net-community.com>
#
#  This file is part of the GNUstep Base Library.
#
#  This library is free software; you can redistribute it and/or
#  modify it under the terms of the GNU General Public
#  License as published by the Free Software Foundation; either
#  version 2 of the License, or (at your option) any later version.
#
#  This library is distributed in the hope that it will be useful,
#  but WITHOUT ANY WARRANTY; without even the implied warranty of
#  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.	 See the GNU
#  General Public License for more details.
#
#  You should have received a copy of the GNU General Public
#  License along with this library; if not, write to the Free
#  Software Foundation, Inc., 51 Franklin Street, Fifth Floor,
#  Boston, MA 02111 USA
#

PACKAGE_NAME = CocoaLumberjack
FRAMEWORK_NAME = CocoaLumberjack

#
# The list of source files
#
CocoaLumberjack_OBJC_FILES = \
CLI/CLIColor.m \
DDASLLogCapture.m \
DDFileLogger.m \
DDOSLogger.m \
DDTTYLogger.m \
Extensions/DDContextFilterLogFormatter.m \
Extensions/DDFileLogger+Buffering.m \
Extensions/DDMultiFormatter.m \
Extensions/DDDispatchQueueLogFormatter.m \
Extensions/DDContextFilterLogFormatter+Deprecated.m \
DDAbstractDatabaseLogger.m \
DDLog.m \
DDASLLogger.m \
DDLoggerNames.m

CocoaLumberjack_HEADER_FILES = \
DDFileLogger+Internal.h \
Supporting Files/DDLegacyMacros.h \
Supporting Files/CocoaLumberjack.h \
include/CocoaLumberjack/DDDispatchQueueLogFormatter.h \
include/CocoaLumberjack/DDAbstractDatabaseLogger.h \
include/CocoaLumberjack/DDLog.h \
include/CocoaLumberjack/DDTTYLogger.h \
include/CocoaLumberjack/DDASLLogCapture.h \
include/CocoaLumberjack/DDASLLogger.h \
include/CocoaLumberjack/DDAssertMacros.h \
include/CocoaLumberjack/DDFileLogger+Buffering.h \
include/CocoaLumberjack/DDContextFilterLogFormatter.h \
include/CocoaLumberjack/DDMultiFormatter.h \
include/CocoaLumberjack/DDLog+LOGV.h \
include/CocoaLumberjack/DDLoggerNames.h \
include/CocoaLumberjack/CLIColor.h \
include/CocoaLumberjack/DDOSLogger.h \
include/CocoaLumberjack/DDLogMacros.h \
include/CocoaLumberjack/DDContextFilterLogFormatter+Deprecated.h \
include/CocoaLumberjack/DDFileLogger.h

CocoaLumberjack_RESOURCE_FILES = Supporting\ Files/CocoaLumberjack-Info.plist

-include Makefile.preamble

include $(GNUSTEP_MAKEFILES)/aggregate.make
include $(GNUSTEP_MAKEFILES)/framework.make

-include Makefile.postamble
