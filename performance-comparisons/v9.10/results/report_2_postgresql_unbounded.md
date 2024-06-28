### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.MarkAllAsReadByTeam | avg | 3ms | 27ms | 24ms | 772.65
| SchemeStore.GetAllPage | avg | 2ms | 13ms | 11ms | 540.46
| CommandWebhookStore.Cleanup | avg | 2ms | 7ms | 5ms | 300.24
| TokenStore.Cleanup | avg | 5ms | 17ms | 12ms | 259.74
| PostPersistentNotificationStore.Get | avg | 6ms | 13ms | 7ms | 109.96
| JobStore.GetNewestJobByStatusesAndType | avg | 5ms | 10ms | 5ms | 96.93
| JobStore.Save | avg | 6ms | 12ms | 6ms | 95.10
| JobStore.GetCountByStatusAndType | avg | 8ms | 14ms | 6ms | 79.75
| ChannelStore.AutocompleteInTeamForSearch | avg | 72ms | 123ms | 51ms | 70.69
| RoleStore.ChannelHigherScopedPermissions | avg | 6ms | 10ms | 4ms | 66.77
| JobStore.GetAllByTypePage | avg | 8ms | 13ms | 5ms | 65.99
| ThreadStore.Get | avg | 7ms | 11ms | 4ms | 54.65
| JobStore.UpdateStatusOptimistically | avg | 9ms | 14ms | 5ms | 54.39
| PostStore.GetPostReminderMetadata | avg | 10ms | 15ms | 5ms | 50.16
| ChannelStore.GetMembers | avg | 4ms | 6ms | 2ms | 45.23
| PostStore.AnalyticsPostCount | avg | 347ms | 495ms | 148ms | 42.66
| PostPersistentNotificationStore.DeleteExpired | avg | 7ms | 10ms | 3ms | 40.73
| ChannelStore.GetMembersForUserWithPagination | avg | 13ms | 18ms | 5ms | 37.94
| PostPriorityStore.GetForPost | avg | 7ms | 9ms | 2ms | 28.96
| UserStore.GetByUsername | avg | 11ms | 14ms | 3ms | 26.36
| ComplianceStore.MessageExport | avg | 15ms | 19ms | 4ms | 26.28
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 28ms | 35ms | 7ms | 24.97
| UserStore.GetProfilesInChannel | avg | 123ms | 151ms | 28ms | 22.71
| ChannelStore.GetMember | avg | 9ms | 11ms | 2ms | 22.55
| UserStore.GetProfilesNotInChannel | avg | 18ms | 22ms | 4ms | 22.54
| PostStore.SetPostReminder | avg | 23ms | 28ms | 5ms | 21.70
| PostStore.Update | avg | 27ms | 32ms | 5ms | 18.43
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 28ms | 33ms | 5ms | 18.05
| SessionStore.GetSessionsExpired | avg | 12ms | 14ms | 2ms | 16.58
| ChannelStore.UpdateSidebarCategories | avg | 106ms | 122ms | 16ms | 15.07
| SessionStore.Get | avg | 14ms | 16ms | 2ms | 13.88
| PostStore.SearchPostsForUser | avg | 241ms | 263ms | 22ms | 9.13
| ChannelStore.GetSidebarCategory | avg | 32ms | 34ms | 2ms | 6.18
| ChannelStore.CreateInitialSidebarCategories | avg | 41ms | 43ms | 2ms | 4.91
| ProductNoticesStore.View | avg | 62ms | 64ms | 2ms | 3.23
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ThreadStore.MarkAllAsReadByTeam | p99 | 5ms | 98ms | 93ms | 1878.79
| ChannelStore.AutocompleteInTeamForSearch | p99 | 246ms | 2.762s | 2.516s | 1022.35
| SchemeStore.GetAllPage | p99 | 5ms | 25ms | 20ms | 404.04
| PostPersistentNotificationStore.Get | p99 | 45ms | 221ms | 176ms | 393.29
| CommandWebhookStore.Cleanup | p99 | 5ms | 24ms | 19ms | 383.65
| SessionStore.GetSessionsExpired | p99 | 49ms | 236ms | 187ms | 382.61
| PostPersistentNotificationStore.DeleteExpired | p99 | 47ms | 191ms | 144ms | 303.95
| ChannelStore.GetMembersForUserWithPagination | p99 | 47ms | 187ms | 140ms | 297.87
| JobStore.GetNewestJobByStatusesAndType | p99 | 35ms | 132ms | 97ms | 276.48
| JobStore.GetAllByTypePage | p99 | 25ms | 93ms | 68ms | 276.19
| JobStore.Save | p99 | 46ms | 154ms | 108ms | 236.39
| JobStore.UpdateStatusOptimistically | p99 | 47ms | 153ms | 106ms | 223.16
| JobStore.GetCountByStatusAndType | p99 | 98ms | 275ms | 177ms | 180.15
| PostStore.GetPostReminderMetadata | p99 | 84ms | 189ms | 105ms | 124.63
| TokenStore.Cleanup | p99 | 24ms | 50ms | 26ms | 106.56
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 5ms | 10ms | 5ms | 101.01
| PluginStore.Get | p99 | 5ms | 10ms | 5ms | 101.01
| ChannelStore.GetMembers | p99 | 5ms | 10ms | 5ms | 100.97
| UserStore.GetProfilesNotInChannel | p99 | 49ms | 97ms | 48ms | 97.96
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 48ms | 91ms | 43ms | 89.12
| UserStore.GetMany | p99 | 45ms | 85ms | 40ms | 88.36
| UserStore.GetByUsername | p99 | 98ms | 183ms | 85ms | 86.94
| PostAcknowledgementStore.GetForPost | p99 | 62ms | 83ms | 21ms | 33.87
| ThreadStore.Get | p99 | 72ms | 95ms | 23ms | 31.87
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 306ms | 385ms | 79ms | 25.80
| JobStore.Get | p99 | 170ms | 213ms | 43ms | 25.34
| ChannelStore.CreateDirectChannel | p99 | 474ms | 560ms | 86ms | 18.16
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 192ms | 226ms | 34ms | 17.67
| ThreadStore.GetTeamsUnreadForUser | p99 | 102ms | 116ms | 14ms | 13.67
| PostStore.Update | p99 | 205ms | 230ms | 25ms | 12.21
| ComplianceStore.MessageExport | p99 | 195ms | 216ms | 21ms | 10.79
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 79ms | 87ms | 8ms | 10.15
| ChannelStore.SearchGroupChannels | p99 | 110ms | 121ms | 11ms | 9.99
| FileInfoStore.AttachToPost | p99 | 179ms | 194ms | 15ms | 8.36
| PostPriorityStore.GetForPost | p99 | 93ms | 100ms | 7ms | 7.53
| TeamStore.GetMember | p99 | 43ms | 46ms | 3ms | 7.05
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 70ms | 74ms | 4ms | 5.75
| UserStore.GetAllProfiles | p99 | 52ms | 55ms | 3ms | 5.75
| PluginStore.Delete | p99 | 55ms | 58ms | 3ms | 5.43
| SystemStore.GetByName | p99 | 76ms | 80ms | 4ms | 5.28
| UserStore.UpdateUpdateAt | p99 | 63ms | 66ms | 3ms | 4.79
| ReactionStore.GetForPost | p99 | 84ms | 88ms | 4ms | 4.75
| UserStore.UpdateLastLogin | p99 | 65ms | 68ms | 3ms | 4.61
| PostStore.SetPostReminder | p99 | 224ms | 234ms | 10ms | 4.47
| ChannelStore.GetMember | p99 | 95ms | 99ms | 4ms | 4.22
| ChannelStore.GetPublicChannelsForTeam | p99 | 161ms | 167ms | 6ms | 3.74
| ThreadStore.MarkAsRead | p99 | 83ms | 86ms | 3ms | 3.61
| ChannelStore.GetPinnedPostCount | p99 | 88ms | 91ms | 3ms | 3.41
| ThreadStore.GetMembershipForUser | p99 | 91ms | 94ms | 3ms | 3.30
| ChannelStore.CreateInitialSidebarCategories | p99 | 412ms | 424ms | 12ms | 2.91
| SessionStore.Get | p99 | 185ms | 190ms | 5ms | 2.70
| UserStore.Get | p99 | 80ms | 82ms | 2ms | 2.50
| PostAcknowledgementStore.GetForPosts | p99 | 162ms | 166ms | 4ms | 2.47
| ThreadStore.MaintainMembership | p99 | 210ms | 215ms | 5ms | 2.38
| TeamStore.GetTeamsByUserId | p99 | 84ms | 86ms | 2ms | 2.38
| PreferenceStore.Save | p99 | 224ms | 229ms | 5ms | 2.23
| UserStore.AutocompleteUsersInChannel | p99 | 352ms | 359ms | 7ms | 1.99
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| DesktopTokensStore.DeleteOlderThan | avg | 2ms | 0s | -2ms | -113.84
| ChannelStore.GetMemberCountsByGroup | avg | 14ms | 0s | -14ms | -100.72
| ChannelStore.GetByNameIncludeDeleted | avg | 74ms | 0s | -74ms | -99.93
| DraftStore.Delete | avg | 32ms | 2ms | -30ms | -95.13
| DraftStore.Get | avg | 19ms | 2ms | -17ms | -91.61
| ChannelStore.CreateSidebarCategory | avg | 126ms | 42ms | -84ms | -66.75
| RetentionPolicyStore.GetCount | avg | 9ms | 3ms | -6ms | -66.33
| RetentionPolicyStore.GetAll | avg | 7ms | 3ms | -4ms | -59.96
| UserAccessTokenStore.GetByToken | avg | 20ms | 8ms | -12ms | -59.66
| ChannelStore.GetTeamChannels | avg | 54ms | 24ms | -30ms | -55.63
| PreferenceStore.DeleteCategoryAndName | avg | 13ms | 6ms | -7ms | -54.20
| PluginStore.List | avg | 16ms | 9ms | -7ms | -44.04
| LicenseStore.GetAll | avg | 5ms | 3ms | -2ms | -42.25
| PostStore.Delete | avg | 52ms | 31ms | -21ms | -40.59
| EmojiStore.GetMultipleByName | avg | 10ms | 6ms | -4ms | -39.15
| LinkMetadataStore.Save | avg | 9ms | 6ms | -3ms | -34.91
| ChannelStore.Save | avg | 50ms | 34ms | -16ms | -32.19
| UserStore.AnalyticsActiveCount | avg | 54ms | 38ms | -16ms | -29.77
| SessionStore.Remove | avg | 12ms | 9ms | -3ms | -24.75
| PostStore.GetPostReminders | avg | 21ms | 16ms | -5ms | -23.48
| ProductNoticesStore.ClearOldNotices | avg | 48ms | 37ms | -11ms | -23.00
| TeamStore.GetActiveMemberCount | avg | 83ms | 65ms | -18ms | -21.58
| BotStore.Get | avg | 9ms | 7ms | -2ms | -21.14
| TeamStore.GetTotalMemberCount | avg | 80ms | 64ms | -16ms | -20.03
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 11ms | 9ms | -2ms | -18.31
| ChannelStore.GetPublicChannelsForTeam | avg | 34ms | 28ms | -6ms | -17.90
| ChannelStore.CreateDirectChannel | avg | 80ms | 73ms | -7ms | -8.72
| UserStore.AutocompleteUsersInChannel | avg | 74ms | 71ms | -3ms | -4.08
| ChannelStore.Autocomplete | avg | 60ms | 58ms | -2ms | -3.34
| UserStore.GetAllProfilesInChannel | avg | 425ms | 415ms | -10ms | -2.35
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| DesktopTokensStore.DeleteOlderThan | p99 | 5ms | 0s | -5ms | -100.95
| ChannelStore.GetByNameIncludeDeleted | p99 | 100ms | 0s | -100ms | -100.50
| ChannelStore.GetMemberCountsByGroup | p99 | 69ms | 0s | -69ms | -100.00
| DraftStore.Delete | p99 | 99ms | 5ms | -94ms | -94.95
| DraftStore.Get | p99 | 95ms | 5ms | -90ms | -94.74
| UserAccessTokenStore.GetByToken | p99 | 365ms | 60ms | -305ms | -83.56
| RetentionPolicyStore.GetAll | p99 | 25ms | 5ms | -20ms | -81.47
| ChannelStore.GetTeamChannels | p99 | 241ms | 48ms | -193ms | -80.08
| ChannelStore.CreateSidebarCategory | p99 | 488ms | 98ms | -390ms | -80.00
| RetentionPolicyStore.GetCount | p99 | 25ms | 10ms | -15ms | -60.73
| PluginStore.List | p99 | 224ms | 88ms | -136ms | -60.71
| UserStore.AnalyticsActiveCount | p99 | 244ms | 98ms | -146ms | -59.84
| TeamStore.GetActiveMemberCount | p99 | 244ms | 100ms | -144ms | -59.02
| PostStore.GetPostReminders | p99 | 230ms | 94ms | -136ms | -59.00
| LinkMetadataStore.Save | p99 | 175ms | 76ms | -99ms | -56.57
| UserStore.Count | p99 | 201ms | 95ms | -106ms | -52.87
| PostStore.Delete | p99 | 465ms | 224ms | -241ms | -51.83
| SessionStore.Remove | p99 | 94ms | 47ms | -47ms | -50.13
| EmojiStore.GetMultipleByName | p99 | 48ms | 24ms | -24ms | -50.00
| ProductNoticesStore.ClearOldNotices | p99 | 99ms | 50ms | -49ms | -49.49
| BotStore.Get | p99 | 93ms | 48ms | -45ms | -48.65
| ChannelStore.Save | p99 | 407ms | 230ms | -177ms | -43.50
| JobStore.GetAllByStatus | p99 | 146ms | 113ms | -33ms | -22.58
| JobStore.UpdateStatus | p99 | 198ms | 154ms | -44ms | -22.19
| ChannelStore.UpdateSidebarCategories | p99 | 912ms | 730ms | -182ms | -19.96
| StatusStore.GetByIds | p99 | 121ms | 98ms | -23ms | -19.07
| ClusterDiscoveryStore.SetLastPingAt | p99 | 117ms | 96ms | -21ms | -17.95
| JobStore.UpdateOptimistically | p99 | 113ms | 95ms | -18ms | -15.99
| StatusStore.SaveOrUpdate | p99 | 377ms | 319ms | -58ms | -15.38
| ChannelStore.GetMemberForPost | p99 | 135ms | 117ms | -18ms | -13.37
| PluginStore.SetWithOptions | p99 | 114ms | 99ms | -15ms | -13.17
| ProductNoticesStore.View | p99 | 565ms | 496ms | -69ms | -12.21
| UserStore.Save | p99 | 349ms | 315ms | -34ms | -9.74
| FileInfoStore.SetContent | p99 | 210ms | 190ms | -20ms | -9.52
| ChannelStore.GetMemberCount | p99 | 191ms | 174ms | -17ms | -8.90
| StatusStore.UpdateExpiredDNDStatuses | p99 | 48ms | 44ms | -4ms | -8.27
| ThreadStore.GetThreadsForUser | p99 | 107ms | 99ms | -8ms | -7.50
| ChannelMemberHistoryStore.GetUsersInChannelDuring | p99 | 442ms | 412ms | -30ms | -6.79
| WebhookStore.GetOutgoingByTeam | p99 | 130ms | 122ms | -8ms | -6.17
| PostStore.GetPostIdAfterTime | p99 | 66ms | 62ms | -4ms | -6.06
| ThreadStore.GetThreadFollowers | p99 | 91ms | 86ms | -5ms | -5.51
| SessionStore.Save | p99 | 137ms | 130ms | -7ms | -5.10
| ChannelStore.GetMemberLastViewedAt | p99 | 80ms | 76ms | -4ms | -5.02
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 91ms | 87ms | -4ms | -4.38
| ThreadStore.GetThreadForUser | p99 | 188ms | 180ms | -8ms | -4.26
| PreferenceStore.DeleteCategoryAndName | p99 | 48ms | 46ms | -2ms | -4.15
| ChannelStore.GetFileCount | p99 | 98ms | 94ms | -4ms | -4.08
| PostStore.GetPostsSince | p99 | 200ms | 193ms | -7ms | -3.49
| StatusStore.UpdateLastActivityAt | p99 | 86ms | 83ms | -3ms | -3.48
| ChannelStore.GetByName | p99 | 92ms | 89ms | -3ms | -3.26
| ThreadStore.MarkAllAsReadByChannels | p99 | 96ms | 93ms | -3ms | -3.12
| PostStore.Save | p99 | 301ms | 292ms | -9ms | -2.99
| PostStore.GetPostsBefore | p99 | 102ms | 99ms | -3ms | -2.94
| PostStore.GetPosts | p99 | 76ms | 74ms | -2ms | -2.63
| UserStore.UpdateFailedPasswordAttempts | p99 | 81ms | 79ms | -2ms | -2.48
| ThreadStore.GetTotalUnreadThreads | p99 | 87ms | 85ms | -2ms | -2.30
| ThreadStore.GetTotalThreads | p99 | 88ms | 86ms | -2ms | -2.29
| ChannelStore.GetGuestCount | p99 | 90ms | 88ms | -2ms | -2.22
| FileInfoStore.Save | p99 | 98ms | 96ms | -2ms | -2.03
| UserStore.GetProfilesByUsernames | p99 | 99ms | 97ms | -2ms | -2.02
| ChannelStore.Get | p99 | 99ms | 97ms | -2ms | -2.01
| ChannelStore.GetChannelUnread | p99 | 100ms | 98ms | -2ms | -2.01
| PostStore.Get | p99 | 220ms | 216ms | -4ms | -1.82
| ChannelStore.GetSidebarCategory | p99 | 236ms | 232ms | -4ms | -1.69
| UserStore.GetAllProfilesInChannel | p99 | 2.172s | 2.139s | -33ms | -1.52
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | avg | 3ms | 27ms | 24ms | 751.43
| getRolesByNames | avg | 3ms | 15ms | 12ms | 432.60
| getJobsByType | avg | 8ms | 14ms | 6ms | 70.59
| autocompleteChannelsForTeamForSearch | avg | 72ms | 123ms | 51ms | 70.58
| getFilteredUsersStats | avg | 20ms | 28ms | 8ms | 40.96
| getChannel | avg | 23ms | 30ms | 7ms | 31.01
| createUser | avg | 237ms | 304ms | 67ms | 28.24
| createDirectChannel | avg | 522ms | 664ms | 142ms | 27.21
| login | avg | 165ms | 207ms | 42ms | 25.41
| createGroupChannel | avg | 856ms | 1.048s | 192ms | 22.43
| removeUserCustomStatus | avg | 336ms | 392ms | 56ms | 16.64
| addChannelMember | avg | 472ms | 550ms | 78ms | 16.51
| getUser | avg | 12ms | 14ms | 2ms | 16.44
| unfollowThreadByUser | avg | 46ms | 52ms | 6ms | 13.10
| updateCategoriesForTeamForUser | avg | 177ms | 198ms | 21ms | 11.90
| getClientConfig | avg | 18ms | 20ms | 2ms | 11.15
| getChannelMember | avg | 20ms | 22ms | 2ms | 9.87
| searchPostsInTeam | avg | 266ms | 289ms | 23ms | 8.65
| getCategoriesForTeamForUser | avg | 29ms | 31ms | 2ms | 6.80
| addTeamMember | avg | 1.287s | 1.349s | 62ms | 4.82
| updateReadStateThreadByUser | avg | 128ms | 131ms | 3ms | 2.34
| getProfileImage | avg | 87ms | 89ms | 2ms | 2.31
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateReadStateAllThreadsByUser | p99 | 5ms | 98ms | 93ms | 1878.79
| autocompleteChannelsForTeamForSearch | p99 | 246ms | 2.762s | 2.516s | 1022.35
| getRolesByNames | p99 | 10ms | 50ms | 40ms | 406.09
| getFilteredUsersStats | p99 | 25ms | 97ms | 72ms | 289.74
| getJobsByType | p99 | 25ms | 93ms | 68ms | 275.67
| logout | p99 | 971ms | 2.125s | 1.154s | 118.82
| updatePreferences | p99 | 249ms | 375ms | 126ms | 50.52
| login | p99 | 1.397s | 1.958s | 561ms | 40.17
| getUserStatusesByIds | p99 | 25ms | 34ms | 9ms | 36.72
| getChannel | p99 | 222ms | 298ms | 76ms | 34.16
| unfollowThreadByUser | p99 | 320ms | 418ms | 98ms | 30.63
| createUser | p99 | 1.616s | 2.088s | 472ms | 29.21
| getPublicChannelsForTeam | p99 | 161ms | 203ms | 42ms | 26.17
| createDirectChannel | p99 | 2.39s | 2.975s | 585ms | 24.48
| getTeamMembersForUser | p99 | 101ms | 122ms | 21ms | 20.79
| getChannelsForTeamForUser | p99 | 111ms | 128ms | 17ms | 15.36
| getAllTeams | p99 | 98ms | 108ms | 10ms | 10.17
| getUser | p99 | 204ms | 224ms | 20ms | 9.79
| addTeamMember | p99 | 6.465s | 7.09s | 625ms | 9.67
| getChannelMembersForTeamForUser | p99 | 99ms | 108ms | 9ms | 9.09
| getUsers | p99 | 199ms | 217ms | 18ms | 9.03
| searchGroupChannels | p99 | 127ms | 138ms | 11ms | 8.66
| createGroupChannel | p99 | 4.156s | 4.507s | 351ms | 8.45
| getUsersByIds | p99 | 39ms | 42ms | 3ms | 7.75
| getTeamsUnreadForUser | p99 | 182ms | 196ms | 14ms | 7.69
| addChannelMember | p99 | 2.33s | 2.466s | 136ms | 5.84
| getTeamsForUser | p99 | 85ms | 89ms | 4ms | 4.69
| getPreferences | p99 | 91ms | 95ms | 4ms | 4.41
| autocompleteUsers | p99 | 304ms | 317ms | 13ms | 4.28
| getChannelMember | p99 | 225ms | 234ms | 9ms | 4.00
| getThreadsForUser | p99 | 137ms | 141ms | 4ms | 2.92
| removeUserCustomStatus | p99 | 2.08s | 2.131s | 51ms | 2.45
| getClientConfig | p99 | 225ms | 230ms | 5ms | 2.22
| updateReadStateThreadByUser | p99 | 829ms | 847ms | 18ms | 2.17
| viewChannel | p99 | 380ms | 388ms | 8ms | 2.11
| saveReaction | p99 | 243ms | 246ms | 3ms | 1.23
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| channelMemberCountsByGroup | avg | 14ms | 0s | -14ms | -97.57
| deleteDraft | avg | 19ms | 4ms | -15ms | -80.54
| createCategoryForTeamForUser | avg | 134ms | 49ms | -85ms | -63.43
| patchPost | avg | 237ms | 97ms | -140ms | -58.98
| upsertDraft | avg | 32ms | 14ms | -18ms | -56.11
| followThreadByUser | avg | 62ms | 28ms | -34ms | -54.93
| deletePost | avg | 84ms | 54ms | -30ms | -35.74
| createChannel | avg | 756ms | 548ms | -208ms | -27.50
| getTeamStats | avg | 120ms | 90ms | -30ms | -25.08
| getAnalytics | avg | 64ms | 55ms | -9ms | -14.11
| logout | avg | 233ms | 202ms | -31ms | -13.29
| getPublicChannelsForTeam | avg | 35ms | 31ms | -4ms | -11.38
| searchAllChannels | avg | 61ms | 59ms | -2ms | -3.30
| autocompleteUsers | avg | 65ms | 63ms | -2ms | -3.08
| getPostsForChannel | avg | 99ms | 96ms | -3ms | -3.03
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getServerLimits | p99 | 5ms | 0s | -5ms | -101.01
| channelMemberCountsByGroup | p99 | 69ms | 0s | -69ms | -99.28
| deleteDraft | p99 | 95ms | 10ms | -85ms | -89.47
| patchPost | p99 | 6.05s | 781ms | -5.269s | -87.09
| createCategoryForTeamForUser | p99 | 488ms | 98ms | -390ms | -80.00
| setPostReminder | p99 | 1.975s | 474ms | -1.501s | -76.00
| followThreadByUser | p99 | 244ms | 98ms | -146ms | -59.91
| createChannel | p99 | 2.44s | 991ms | -1.449s | -59.39
| updateCategoriesForTeamForUser | p99 | 2.102s | 946ms | -1.156s | -54.98
| upsertDraft | p99 | 99ms | 49ms | -50ms | -50.51
| getTeamStats | p99 | 470ms | 247ms | -223ms | -47.45
| getFilePreview | p99 | 290ms | 267ms | -23ms | -7.93
| getUsersByNames | p99 | 106ms | 100ms | -6ms | -5.67
| deletePost | p99 | 465ms | 457ms | -8ms | -1.72
| getPostsForChannel | p99 | 948ms | 937ms | -11ms | -1.16
| searchPostsInTeam | p99 | 2.459s | 2.433s | -26ms | -1.06
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 7ms| 8ms | 1ms | 13.601
| |  P99| 79ms| 79ms | 0s | 0.000
| BotStore.Get |  Avg| 9ms| 7ms | -2ms | -21.143
| |  P99| 93ms| 48ms | -45ms | -48.649
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 118ms| 117ms | -1ms | -0.850
| |  P99| 442ms| 412ms | -30ms | -6.788
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 58ms| 58ms | 0s | 0.000
| ChannelStore.AnalyticsTypeCount |  Avg| 17ms| 17ms | 0s | 0.000
| |  P99| 49ms| 48ms | -1ms | -2.045
| ChannelStore.Autocomplete |  Avg| 60ms| 58ms | -2ms | -3.343
| |  P99| 239ms| 237ms | -2ms | -0.837
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 72ms| 123ms | 51ms | 70.692
| |  P99| 246ms| 2.762s | 2.516s | 1022.349
| ChannelStore.CreateDirectChannel |  Avg| 80ms| 73ms | -7ms | -8.724
| |  P99| 474ms| 560ms | 86ms | 18.155
| ChannelStore.CreateInitialSidebarCategories |  Avg| 41ms| 43ms | 2ms | 4.908
| |  P99| 412ms| 424ms | 12ms | 2.910
| ChannelStore.CreateSidebarCategory |  Avg| 126ms| 42ms | -84ms | -66.752
| |  P99| 488ms| 98ms | -390ms | -79.998
| ChannelStore.Get |  Avg| 12ms| 11ms | -1ms | -8.593
| |  P99| 99ms| 97ms | -2ms | -2.012
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 28ms| 33ms | 5ms | 18.051
| |  P99| 192ms| 226ms | 34ms | 17.667
| ChannelStore.GetAllChannelMembersForUser |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 88ms| 88ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 28ms| 35ms | 7ms | 24.974
| |  P99| 306ms| 385ms | 79ms | 25.797
| ChannelStore.GetByName |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 92ms| 89ms | -3ms | -3.265
| ChannelStore.GetByNameIncludeDeleted |  Avg| 74ms| 0s | -74ms | -99.930
| |  P99| 100ms| 0s | -100ms | -100.503
| ChannelStore.GetChannelUnread |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 100ms| 98ms | -2ms | -2.009
| ChannelStore.GetChannels |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 98ms| 97ms | -1ms | -1.020
| ChannelStore.GetChannelsByUser |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 95ms| 95ms | 0s | 0.000
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 93ms| 92ms | -1ms | -1.074
| ChannelStore.GetFileCount |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 98ms| 94ms | -4ms | -4.081
| ChannelStore.GetGuestCount |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 90ms| 88ms | -2ms | -2.221
| ChannelStore.GetMember |  Avg| 9ms| 11ms | 2ms | 22.551
| |  P99| 95ms| 99ms | 4ms | 4.217
| ChannelStore.GetMemberCount |  Avg| 34ms| 33ms | -1ms | -2.985
| |  P99| 191ms| 174ms | -17ms | -8.903
| ChannelStore.GetMemberCountsByGroup |  Avg| 14ms| 0s | -14ms | -100.718
| |  P99| 69ms| 0s | -69ms | -100.001
| ChannelStore.GetMemberForPost |  Avg| 15ms| 15ms | 0s | 0.000
| |  P99| 135ms| 117ms | -18ms | -13.373
| ChannelStore.GetMemberLastViewedAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 80ms| 76ms | -4ms | -5.020
| ChannelStore.GetMembers |  Avg| 4ms| 6ms | 2ms | 45.234
| |  P99| 5ms| 10ms | 5ms | 100.973
| ChannelStore.GetMembersForUser |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 96ms| 96ms | 0s | 0.000
| ChannelStore.GetMembersForUserWithPagination |  Avg| 13ms| 18ms | 5ms | 37.945
| |  P99| 47ms| 187ms | 140ms | 297.872
| ChannelStore.GetPinnedPostCount |  Avg| 10ms| 9ms | -1ms | -10.227
| |  P99| 88ms| 91ms | 3ms | 3.411
| ChannelStore.GetPublicChannelsForTeam |  Avg| 34ms| 28ms | -6ms | -17.901
| |  P99| 161ms| 167ms | 6ms | 3.738
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 29ms| 30ms | 1ms | 3.459
| |  P99| 223ms| 225ms | 2ms | 0.896
| ChannelStore.GetSidebarCategory |  Avg| 32ms| 34ms | 2ms | 6.179
| |  P99| 236ms| 232ms | -4ms | -1.692
| ChannelStore.GetTeamChannels |  Avg| 54ms| 24ms | -30ms | -55.630
| |  P99| 241ms| 48ms | -193ms | -80.083
| ChannelStore.IncrementMentionCount |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 86ms| 85ms | -1ms | -1.159
| ChannelStore.Save |  Avg| 50ms| 34ms | -16ms | -32.189
| |  P99| 407ms| 230ms | -177ms | -43.502
| ChannelStore.SaveMember |  Avg| 58ms| 58ms | 0s | 0.000
| |  P99| 443ms| 444ms | 1ms | 0.226
| ChannelStore.SearchGroupChannels |  Avg| 14ms| 13ms | -1ms | -7.093
| |  P99| 110ms| 121ms | 11ms | 9.992
| ChannelStore.UpdateLastViewedAt |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 89ms| 89ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 106ms| 122ms | 16ms | 15.066
| |  P99| 912ms| 730ms | -182ms | -19.963
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 79ms| 87ms | 8ms | 10.146
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 117ms| 96ms | -21ms | -17.949
| CommandWebhookStore.Cleanup |  Avg| 2ms| 7ms | 5ms | 300.235
| |  P99| 5ms| 24ms | 19ms | 383.646
| ComplianceStore.MessageExport |  Avg| 15ms| 19ms | 4ms | 26.283
| |  P99| 195ms| 216ms | 21ms | 10.789
| DesktopTokensStore.DeleteOlderThan |  Avg| 2ms| 0s | -2ms | -113.835
| |  P99| 5ms| 0s | -5ms | -100.953
| DraftStore.Delete |  Avg| 32ms| 2ms | -30ms | -95.133
| |  P99| 99ms| 5ms | -94ms | -94.949
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 11ms| 9ms | -2ms | -18.309
| |  P99| 48ms| 91ms | 43ms | 89.119
| DraftStore.Get |  Avg| 19ms| 2ms | -17ms | -91.605
| |  P99| 95ms| 5ms | -90ms | -94.737
| DraftStore.GetDraftsForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 89ms| 89ms | 0s | 0.000
| EmojiStore.GetMultipleByName |  Avg| 10ms| 6ms | -4ms | -39.145
| |  P99| 48ms| 24ms | -24ms | -50.000
| FileInfoStore.AttachToPost |  Avg| 17ms| 18ms | 1ms | 5.871
| |  P99| 179ms| 194ms | 15ms | 8.364
| FileInfoStore.Get |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 98ms| 97ms | -1ms | -1.020
| FileInfoStore.GetForPost |  Avg| 9ms| 10ms | 1ms | 10.592
| |  P99| 93ms| 93ms | 0s | 0.000
| FileInfoStore.Save |  Avg| 12ms| 13ms | 1ms | 8.369
| |  P99| 98ms| 96ms | -2ms | -2.032
| FileInfoStore.SetContent |  Avg| 21ms| 20ms | -1ms | -4.820
| |  P99| 210ms| 190ms | -20ms | -9.516
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 70ms| 74ms | 4ms | 5.750
| GroupStore.GetByName |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 79ms| 80ms | 1ms | 1.273
| GroupStore.GetGroups |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 90ms| 90ms | 0s | 0.000
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 3ms| 2ms | -1ms | -39.281
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 16ms| 17ms | 1ms | 6.348
| |  P99| 170ms| 213ms | 43ms | 25.340
| JobStore.GetAllByStatus |  Avg| 12ms| 11ms | -1ms | -8.432
| |  P99| 146ms| 113ms | -33ms | -22.575
| JobStore.GetAllByTypePage |  Avg| 8ms| 13ms | 5ms | 65.992
| |  P99| 25ms| 93ms | 68ms | 276.194
| JobStore.GetCountByStatusAndType |  Avg| 8ms| 14ms | 6ms | 79.753
| |  P99| 98ms| 275ms | 177ms | 180.153
| JobStore.GetNewestJobByStatusesAndType |  Avg| 5ms| 10ms | 5ms | 96.930
| |  P99| 35ms| 132ms | 97ms | 276.485
| JobStore.Save |  Avg| 6ms| 12ms | 6ms | 95.104
| |  P99| 46ms| 154ms | 108ms | 236.389
| JobStore.UpdateOptimistically |  Avg| 13ms| 12ms | -1ms | -7.843
| |  P99| 113ms| 95ms | -18ms | -15.988
| JobStore.UpdateStatus |  Avg| 11ms| 10ms | -1ms | -8.939
| |  P99| 198ms| 154ms | -44ms | -22.194
| JobStore.UpdateStatusOptimistically |  Avg| 9ms| 14ms | 5ms | 54.391
| |  P99| 47ms| 153ms | 106ms | 223.158
| LicenseStore.GetAll |  Avg| 5ms| 3ms | -2ms | -42.247
| |  P99| 10ms| 10ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 90ms| 89ms | -1ms | -1.111
| LinkMetadataStore.Save |  Avg| 9ms| 6ms | -3ms | -34.907
| |  P99| 175ms| 76ms | -99ms | -56.571
| PluginStore.Delete |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 55ms| 58ms | 3ms | 5.434
| PluginStore.Get |  Avg| 2ms| 3ms | 1ms | 48.186
| |  P99| 5ms| 10ms | 5ms | 101.010
| PluginStore.List |  Avg| 16ms| 9ms | -7ms | -44.042
| |  P99| 224ms| 88ms | -136ms | -60.714
| PluginStore.SetWithOptions |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 114ms| 99ms | -15ms | -13.174
| PostAcknowledgementStore.GetForPost |  Avg| 7ms| 8ms | 1ms | 14.838
| |  P99| 62ms| 83ms | 21ms | 33.871
| PostAcknowledgementStore.GetForPosts |  Avg| 12ms| 13ms | 1ms | 8.043
| |  P99| 162ms| 166ms | 4ms | 2.470
| PostPersistentNotificationStore.DeleteExpired |  Avg| 7ms| 10ms | 3ms | 40.733
| |  P99| 47ms| 191ms | 144ms | 303.953
| PostPersistentNotificationStore.Get |  Avg| 6ms| 13ms | 7ms | 109.962
| |  P99| 45ms| 221ms | 176ms | 393.294
| PostPersistentNotificationStore.GetSingle |  Avg| 7ms| 8ms | 1ms | 13.485
| |  P99| 78ms| 79ms | 1ms | 1.284
| PostPriorityStore.GetForPost |  Avg| 7ms| 9ms | 2ms | 28.957
| |  P99| 93ms| 100ms | 7ms | 7.527
| PostPriorityStore.GetForPosts |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 165ms| 166ms | 1ms | 0.605
| PostStore.AnalyticsPostCount |  Avg| 347ms| 495ms | 148ms | 42.664
| |  P99| 985ms| 990ms | 5ms | 0.508
| PostStore.Delete |  Avg| 52ms| 31ms | -21ms | -40.588
| |  P99| 465ms| 224ms | -241ms | -51.827
| PostStore.Get |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 220ms| 216ms | -4ms | -1.820
| PostStore.GetEtag |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 99ms| 98ms | -1ms | -1.007
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 66ms| 62ms | -4ms | -6.063
| PostStore.GetPostIdBeforeTime |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 90ms| 89ms | -1ms | -1.110
| PostStore.GetPostReminderMetadata |  Avg| 10ms| 15ms | 5ms | 50.160
| |  P99| 84ms| 189ms | 105ms | 124.630
| PostStore.GetPostReminders |  Avg| 21ms| 16ms | -5ms | -23.483
| |  P99| 230ms| 94ms | -136ms | -59.002
| PostStore.GetPosts |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 76ms| 74ms | -2ms | -2.630
| PostStore.GetPostsAfter |  Avg| 10ms| 11ms | 1ms | 9.611
| |  P99| 85ms| 85ms | 0s | 0.000
| PostStore.GetPostsBefore |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 102ms| 99ms | -3ms | -2.944
| PostStore.GetPostsByThread |  Avg| 14ms| 15ms | 1ms | 6.926
| |  P99| 95ms| 96ms | 1ms | 1.055
| PostStore.GetPostsSince |  Avg| 26ms| 25ms | -1ms | -3.917
| |  P99| 200ms| 193ms | -7ms | -3.494
| PostStore.GetSingle |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 88ms| 88ms | 0s | 0.000
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 31ms| 31ms | 0s | 0.000
| |  P99| 301ms| 292ms | -9ms | -2.990
| PostStore.SearchPostsForUser |  Avg| 241ms| 263ms | 22ms | 9.130
| |  P99| 2.411s| 2.39s | -21ms | -0.871
| PostStore.SetPostReminder |  Avg| 23ms| 28ms | 5ms | 21.705
| |  P99| 224ms| 234ms | 10ms | 4.469
| PostStore.Update |  Avg| 27ms| 32ms | 5ms | 18.429
| |  P99| 205ms| 230ms | 25ms | 12.210
| PreferenceStore.DeleteCategoryAndName |  Avg| 13ms| 6ms | -7ms | -54.204
| |  P99| 48ms| 46ms | -2ms | -4.145
| PreferenceStore.Get |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 98ms| 97ms | -1ms | -1.017
| PreferenceStore.GetAll |  Avg| 8ms| 9ms | 1ms | 12.341
| |  P99| 88ms| 89ms | 1ms | 1.143
| PreferenceStore.Save |  Avg| 21ms| 22ms | 1ms | 4.704
| |  P99| 224ms| 229ms | 5ms | 2.233
| ProductNoticesStore.ClearOldNotices |  Avg| 48ms| 37ms | -11ms | -23.001
| |  P99| 99ms| 50ms | -49ms | -49.495
| ProductNoticesStore.GetViews |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 62ms| 64ms | 2ms | 3.234
| |  P99| 565ms| 496ms | -69ms | -12.211
| ReactionStore.GetForPost |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 84ms| 88ms | 4ms | 4.745
| RetentionPolicyStore.GetAll |  Avg| 7ms| 3ms | -4ms | -59.958
| |  P99| 25ms| 5ms | -20ms | -81.466
| RetentionPolicyStore.GetCount |  Avg| 9ms| 3ms | -6ms | -66.334
| |  P99| 25ms| 10ms | -15ms | -60.729
| RoleStore.ChannelHigherScopedPermissions |  Avg| 6ms| 10ms | 4ms | 66.769
| |  P99| 44ms| 44ms | 0s | 0.000
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 2ms| 13ms | 11ms | 540.460
| |  P99| 5ms| 25ms | 20ms | 404.040
| SessionStore.Get |  Avg| 14ms| 16ms | 2ms | 13.880
| |  P99| 185ms| 190ms | 5ms | 2.702
| SessionStore.GetLRUSessions |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 73ms| 72ms | -1ms | -1.368
| SessionStore.GetSessionsExpired |  Avg| 12ms| 14ms | 2ms | 16.577
| |  P99| 49ms| 236ms | 187ms | 382.608
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 91ms| 87ms | -4ms | -4.384
| SessionStore.Remove |  Avg| 12ms| 9ms | -3ms | -24.751
| |  P99| 94ms| 47ms | -47ms | -50.133
| SessionStore.Save |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 137ms| 130ms | -7ms | -5.098
| SessionStore.UpdateLastActivityAt |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 85ms| 84ms | -1ms | -1.181
| StatusStore.Get |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 73ms| 72ms | -1ms | -1.372
| StatusStore.GetByIds |  Avg| 11ms| 12ms | 1ms | 9.098
| |  P99| 121ms| 98ms | -23ms | -19.067
| StatusStore.SaveOrUpdate |  Avg| 24ms| 23ms | -1ms | -4.118
| |  P99| 377ms| 319ms | -58ms | -15.380
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 48ms| 44ms | -4ms | -8.269
| StatusStore.UpdateLastActivityAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 86ms| 83ms | -3ms | -3.479
| SystemStore.GetByName |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 76ms| 80ms | 4ms | 5.282
| TeamStore.AnalyticsTeamCount |  Avg| 8ms| 7ms | -1ms | -13.060
| |  P99| 25ms| 25ms | 0s | 0.000
| TeamStore.Get |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 85ms| 84ms | -1ms | -1.178
| TeamStore.GetActiveMemberCount |  Avg| 83ms| 65ms | -18ms | -21.575
| |  P99| 244ms| 100ms | -144ms | -59.015
| TeamStore.GetAllPage |  Avg| 7ms| 8ms | 1ms | 14.145
| |  P99| 85ms| 85ms | 0s | 0.000
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 85ms| 86ms | 1ms | 1.180
| TeamStore.GetMember |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 43ms| 46ms | 3ms | 7.046
| TeamStore.GetTeamsByUserId |  Avg| 7ms| 8ms | 1ms | 14.161
| |  P99| 84ms| 86ms | 2ms | 2.380
| TeamStore.GetTeamsForUser |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 87ms| 87ms | 0s | 0.000
| TeamStore.GetTotalMemberCount |  Avg| 80ms| 64ms | -16ms | -20.031
| |  P99| 241ms| 240ms | -1ms | -0.415
| TeamStore.SaveMember |  Avg| 42ms| 43ms | 1ms | 2.356
| |  P99| 244ms| 243ms | -1ms | -0.410
| ThreadStore.Get |  Avg| 7ms| 11ms | 4ms | 54.647
| |  P99| 72ms| 95ms | 23ms | 31.871
| ThreadStore.GetMembershipForUser |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 91ms| 94ms | 3ms | 3.297
| ThreadStore.GetTeamsUnreadForUser |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 102ms| 116ms | 14ms | 13.666
| ThreadStore.GetThreadFollowers |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 91ms| 86ms | -5ms | -5.512
| ThreadStore.GetThreadForUser |  Avg| 18ms| 17ms | -1ms | -5.699
| |  P99| 188ms| 180ms | -8ms | -4.257
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 97ms| 98ms | 1ms | 1.032
| ThreadStore.GetThreadsForUser |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 107ms| 99ms | -8ms | -7.496
| ThreadStore.GetTotalThreads |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 88ms| 86ms | -2ms | -2.285
| ThreadStore.GetTotalUnreadMentions |  Avg| 8ms| 9ms | 1ms | 12.081
| |  P99| 87ms| 86ms | -1ms | -1.151
| ThreadStore.GetTotalUnreadThreads |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 87ms| 85ms | -2ms | -2.298
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 8ms| 9ms | 1ms | 11.881
| |  P99| 88ms| 88ms | 0s | 0.000
| ThreadStore.MaintainMembership |  Avg| 18ms| 19ms | 1ms | 5.568
| |  P99| 210ms| 215ms | 5ms | 2.382
| ThreadStore.MarkAllAsReadByChannels |  Avg| 9ms| 10ms | 1ms | 10.663
| |  P99| 96ms| 93ms | -3ms | -3.121
| ThreadStore.MarkAllAsReadByTeam |  Avg| 3ms| 27ms | 24ms | 772.650
| |  P99| 5ms| 98ms | 93ms | 1878.788
| ThreadStore.MarkAsRead |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 83ms| 86ms | 3ms | 3.614
| ThreadStore.UpdateMembership |  Avg| 8ms| 9ms | 1ms | 11.902
| |  P99| 84ms| 84ms | 0s | 0.000
| TokenStore.Cleanup |  Avg| 5ms| 17ms | 12ms | 259.742
| |  P99| 24ms| 50ms | 26ms | 106.557
| UserAccessTokenStore.GetByToken |  Avg| 20ms| 8ms | -12ms | -59.657
| |  P99| 365ms| 60ms | -305ms | -83.561
| UserStore.AnalyticsActiveCount |  Avg| 54ms| 38ms | -16ms | -29.772
| |  P99| 244ms| 98ms | -146ms | -59.836
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 2ms| 3ms | 1ms | 66.302
| |  P99| 5ms| 10ms | 5ms | 101.010
| UserStore.AutocompleteUsersInChannel |  Avg| 74ms| 71ms | -3ms | -4.080
| |  P99| 352ms| 359ms | 7ms | 1.989
| UserStore.Count |  Avg| 26ms| 27ms | 1ms | 3.843
| |  P99| 201ms| 95ms | -106ms | -52.868
| UserStore.Get |  Avg| 6ms| 7ms | 1ms | 15.616
| |  P99| 80ms| 82ms | 2ms | 2.498
| UserStore.GetAllProfiles |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 52ms| 55ms | 3ms | 5.749
| UserStore.GetAllProfilesInChannel |  Avg| 425ms| 415ms | -10ms | -2.353
| |  P99| 2.172s| 2.139s | -33ms | -1.519
| UserStore.GetByUsername |  Avg| 11ms| 14ms | 3ms | 26.358
| |  P99| 98ms| 183ms | 85ms | 86.939
| UserStore.GetForLogin |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 82ms| 82ms | 0s | 0.000
| UserStore.GetMany |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 45ms| 85ms | 40ms | 88.364
| UserStore.GetProfileByIds |  Avg| 10ms| 11ms | 1ms | 9.567
| |  P99| 98ms| 98ms | 0s | 0.000
| UserStore.GetProfilesByUsernames |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 99ms| 97ms | -2ms | -2.019
| UserStore.GetProfilesInChannel |  Avg| 123ms| 151ms | 28ms | 22.709
| |  P99| 247ms| 248ms | 1ms | 0.405
| UserStore.GetProfilesNotInChannel |  Avg| 18ms| 22ms | 4ms | 22.535
| |  P99| 49ms| 97ms | 48ms | 97.959
| UserStore.GetUnreadCount |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 89ms| 89ms | 0s | 0.000
| UserStore.IsEmpty |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 39ms| 40ms | 1ms | 2.551
| UserStore.Save |  Avg| 85ms| 85ms | 0s | 0.000
| |  P99| 349ms| 315ms | -34ms | -9.736
| UserStore.Search |  Avg| 53ms| 52ms | -1ms | -1.892
| |  P99| 231ms| 230ms | -1ms | -0.433
| UserStore.Update |  Avg| 23ms| 24ms | 1ms | 4.276
| |  P99| 223ms| 223ms | 0s | 0.000
| UserStore.UpdateFailedPasswordAttempts |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 81ms| 79ms | -2ms | -2.480
| UserStore.UpdateLastLogin |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 65ms| 68ms | 3ms | 4.614
| UserStore.UpdateUpdateAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 63ms| 66ms | 3ms | 4.786
| UserTermsOfServiceStore.GetByUser |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 79ms| 79ms | 0s | 0.000
| WebhookStore.GetOutgoingByTeam |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 130ms| 122ms | -8ms | -6.174
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 472ms| 550ms | 78ms | 16.511
| | P99| 2.33s| 2.466s | 136ms | 5.837
| addTeamMember | Avg| 1.287s| 1.349s | 62ms | 4.819
| | P99| 6.465s| 7.09s | 625ms | 9.667
| autocompleteChannelsForTeamForSearch | Avg| 72ms| 123ms | 51ms | 70.579
| | P99| 246ms| 2.762s | 2.516s | 1022.349
| autocompleteUsers | Avg| 65ms| 63ms | -2ms | -3.084
| | P99| 304ms| 317ms | 13ms | 4.275
| channelMemberCountsByGroup | Avg| 14ms| 0s | -14ms | -97.568
| | P99| 69ms| 0s | -69ms | -99.281
| createCategoryForTeamForUser | Avg| 134ms| 49ms | -85ms | -63.426
| | P99| 488ms| 98ms | -390ms | -79.995
| createChannel | Avg| 756ms| 548ms | -208ms | -27.497
| | P99| 2.44s| 991ms | -1.449s | -59.385
| createDirectChannel | Avg| 522ms| 664ms | 142ms | 27.214
| | P99| 2.39s| 2.975s | 585ms | 24.479
| createGroupChannel | Avg| 856ms| 1.048s | 192ms | 22.433
| | P99| 4.156s| 4.507s | 351ms | 8.445
| createPost | Avg| 799ms| 797ms | -2ms | -0.250
| | P99| 4.405s| 4.4s | -5ms | -0.114
| createUser | Avg| 237ms| 304ms | 67ms | 28.238
| | P99| 1.616s| 2.088s | 472ms | 29.213
| deleteDraft | Avg| 19ms| 4ms | -15ms | -80.541
| | P99| 95ms| 10ms | -85ms | -89.474
| deletePost | Avg| 84ms| 54ms | -30ms | -35.742
| | P99| 465ms| 457ms | -8ms | -1.720
| followThreadByUser | Avg| 62ms| 28ms | -34ms | -54.929
| | P99| 244ms| 98ms | -146ms | -59.910
| getAllTeams | Avg| 9ms| 10ms | 1ms | 11.483
| | P99| 98ms| 108ms | 10ms | 10.170
| getAnalytics | Avg| 64ms| 55ms | -9ms | -14.105
| | P99| 243ms| 242ms | -1ms | -0.411
| getCategoriesForTeamForUser | Avg| 29ms| 31ms | 2ms | 6.803
| | P99| 226ms| 228ms | 2ms | 0.886
| getChannel | Avg| 23ms| 30ms | 7ms | 31.011
| | P99| 222ms| 298ms | 76ms | 34.162
| getChannelMember | Avg| 20ms| 22ms | 2ms | 9.871
| | P99| 225ms| 234ms | 9ms | 4.001
| getChannelMembers | Avg| 6ms| 7ms | 1ms | 17.484
| | P99| 10ms| 10ms | 0s | 0.000
| getChannelMembersForTeamForUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 99ms| 108ms | 9ms | 9.095
| getChannelStats | Avg| 6ms| 7ms | 1ms | 15.414
| | P99| 98ms| 98ms | 0s | 0.000
| getChannelUnread | Avg| 12ms| 13ms | 1ms | 8.120
| | P99| 132ms| 133ms | 1ms | 0.758
| getChannelsForTeamForUser | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 111ms| 128ms | 17ms | 15.364
| getChannelsForUser | Avg| 11ms| 12ms | 1ms | 8.734
| | P99| 97ms| 96ms | -1ms | -1.035
| getClientConfig | Avg| 18ms| 20ms | 2ms | 11.147
| | P99| 225ms| 230ms | 5ms | 2.221
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getFilePreview | Avg| 65ms| 64ms | -1ms | -1.541
| | P99| 290ms| 267ms | -23ms | -7.929
| getFileThumbnail | Avg| 53ms| 53ms | 0s | 0.000
| | P99| 246ms| 245ms | -1ms | -0.406
| getFilteredUsersStats | Avg| 20ms| 28ms | 8ms | 40.962
| | P99| 25ms| 97ms | 72ms | 289.738
| getJobsByType | Avg| 8ms| 14ms | 6ms | 70.589
| | P99| 25ms| 93ms | 68ms | 275.672
| getPostThread | Avg| 54ms| 55ms | 1ms | 1.844
| | P99| 438ms| 435ms | -3ms | -0.685
| getPostsForChannel | Avg| 99ms| 96ms | -3ms | -3.034
| | P99| 948ms| 937ms | -11ms | -1.161
| getPostsForChannelAroundLastUnread | Avg| 46ms| 47ms | 1ms | 2.165
| | P99| 443ms| 446ms | 3ms | 0.677
| getPreferences | Avg| 9ms| 9ms | 0s | 0.000
| | P99| 91ms| 95ms | 4ms | 4.414
| getPrevTrialLicense | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 10ms| 10ms | 0s | 0.000
| getProfileImage | Avg| 87ms| 89ms | 2ms | 2.306
| | P99| 479ms| 482ms | 3ms | 0.627
| getPublicChannelsForTeam | Avg| 35ms| 31ms | -4ms | -11.379
| | P99| 161ms| 203ms | 42ms | 26.168
| getRolesByNames | Avg| 3ms| 15ms | 12ms | 432.596
| | P99| 10ms| 50ms | 40ms | 406.091
| getServerLimits | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getTeamMember | Avg| 11ms| 10ms | -1ms | -9.239
| | P99| 99ms| 99ms | 0s | 0.000
| getTeamMembersForUser | Avg| 10ms| 10ms | 0s | 0.000
| | P99| 101ms| 122ms | 21ms | 20.786
| getTeamStats | Avg| 120ms| 90ms | -30ms | -25.080
| | P99| 470ms| 247ms | -223ms | -47.446
| getTeamsForUser | Avg| 7ms| 8ms | 1ms | 13.873
| | P99| 85ms| 89ms | 4ms | 4.688
| getTeamsUnreadForUser | Avg| 14ms| 15ms | 1ms | 7.007
| | P99| 182ms| 196ms | 14ms | 7.691
| getThreadsForUser | Avg| 13ms| 14ms | 1ms | 7.436
| | P99| 137ms| 141ms | 4ms | 2.919
| getUser | Avg| 12ms| 14ms | 2ms | 16.438
| | P99| 204ms| 224ms | 20ms | 9.789
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 25ms| 34ms | 9ms | 36.716
| getUsers | Avg| 13ms| 14ms | 1ms | 7.996
| | P99| 199ms| 217ms | 18ms | 9.026
| getUsersByIds | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 39ms| 42ms | 3ms | 7.746
| getUsersByNames | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 106ms| 100ms | -6ms | -5.670
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| login | Avg| 165ms| 207ms | 42ms | 25.406
| | P99| 1.397s| 1.958s | 561ms | 40.167
| logout | Avg| 233ms| 202ms | -31ms | -13.288
| | P99| 971ms| 2.125s | 1.154s | 118.816
| patchPost | Avg| 237ms| 97ms | -140ms | -58.984
| | P99| 6.05s| 781ms | -5.269s | -87.089
| removeUserCustomStatus | Avg| 336ms| 392ms | 56ms | 16.643
| | P99| 2.08s| 2.131s | 51ms | 2.452
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 34ms| 35ms | 1ms | 2.930
| | P99| 243ms| 246ms | 3ms | 1.235
| searchAllChannels | Avg| 61ms| 59ms | -2ms | -3.304
| | P99| 240ms| 239ms | -1ms | -0.417
| searchGroupChannels | Avg| 14ms| 14ms | 0s | 0.000
| | P99| 127ms| 138ms | 11ms | 8.658
| searchPostsInTeam | Avg| 266ms| 289ms | 23ms | 8.654
| | P99| 2.459s| 2.433s | -26ms | -1.058
| searchUsers | Avg| 55ms| 55ms | 0s | 0.000
| | P99| 233ms| 233ms | 0s | 0.000
| setPostReminder | Avg| 87ms| 86ms | -1ms | -1.148
| | P99| 1.975s| 474ms | -1.501s | -76.002
| unfollowThreadByUser | Avg| 46ms| 52ms | 6ms | 13.103
| | P99| 320ms| 418ms | 98ms | 30.626
| updateCategoriesForTeamForUser | Avg| 177ms| 198ms | 21ms | 11.898
| | P99| 2.102s| 946ms | -1.156s | -54.983
| updatePreferences | Avg| 34ms| 35ms | 1ms | 2.958
| | P99| 249ms| 375ms | 126ms | 50.525
| updateReadStateAllThreadsByUser | Avg| 3ms| 27ms | 24ms | 751.432
| | P99| 5ms| 98ms | 93ms | 1878.788
| updateReadStateThreadByUser | Avg| 128ms| 131ms | 3ms | 2.336
| | P99| 829ms| 847ms | 18ms | 2.170
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 482ms| 486ms | 4ms | 0.831
| | P99| 2.135s| 2.135s | 0s | 0.000
| upsertDraft | Avg| 32ms| 14ms | -18ms | -56.109
| | P99| 99ms| 49ms | -50ms | -50.505
| viewChannel | Avg| 39ms| 40ms | 1ms | 2.570
| | P99| 380ms| 388ms | 8ms | 2.105
